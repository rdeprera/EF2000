Tactcom Read-me File.
(c) 1996, Digital Image Design ltd

This document contains  the most up-to-date information about Tactcom.

1. Installation
2. Improvements 
2.1 New head-to-head play
2.2 Custom AA replay button
3. Network games
4. Manual Errata
5. Configuration
6. Mission debriefs
7. Ocean Helpline's EF2000 and Tactcom troubleshooting guide

1. Installation

The installation procedure is straight forward. Please ensure that the files 
setting in your config.sys is set higher than 25 and that the buffers setting 
is more than 35.

2. Improvements

2.1 New head-to-head play

One section of the game is not fully documented in the Tactcom operation 
manual. The new section is a Team based multi-player King of the skies 
section. When the server in a multi-player game selects quick combat, they 
will be able to choose what kind of game they want. The original solo
King-of-the-skies game is still present although the server can select one
of two bases for each player to start at.

There are also two other types, TEAM and BASE DEFENCE. Team allows the server
to nominate two teams, red and green, and enables them to choose which base a
particular player will launch from. Base defence works in  similar way but 
the teams have a single base which they must defend from attack. Points are 
scored for destroying ground targets and a bonus is awarded for a successful 
landing (coming to a complete halt on the runway with your engines turned off).


2.2 Custom AA replay button

Once you have set-up and played a custom AA mission, there is a button 
available which allows you to re-run the last game set-up.

3. Network games

As a result of the upgrades made to the networking and campaign in Tactcom,
It is recommended that a maximum of four players engage in networked
campaign missions. This is due to the complexity of the information that is
required by all the machines. The option for eight players is still available
but the players may experience occasional problems due to loss of information
between computers on a network.

If any of the players linked to a game in network mode decide to leave the 
game then the game must be restarted. All players should exit the mission 
they are on and the server machine must click on the reset network button 
on the multi-player screen.

4. Manual Errata

Page 2 Modem section, INIT should read Initialisation string.

Page 14 AIM 9S should read AIM 9M

Page 30 There are new options in Custom Air-to-Air. These are:
	Height - This allows you to select the altitude of a specific flight.
	Position - This lets you determine relative position of the specific
	flight to you.

Page 31 You no longer go to the arming screen after accepting a custom Air-to-Air
	Mission

On certain images there may be a help button visible on the GUI. This feature is
not present in TACTCOM.

5. Configuration

If you change the setup of the sound on Tactcom, it is advisable to reconfigure
the joystick. This is because the joystick readings are different with sound configured.

6. Mission debriefs

On modem-linked games you may experience inaccuracies between the game and the debriefs.
This is due to the data transfer rate being low. A faster baud rate will improve the
situation if it is available on both modems being used. 

7. Ocean Helpline's EF2000 TACTCOM Troubleshooting guide.
   =====================================================

It is important to note that EF2000 is a DOS based game and wasn't designed
to work with Windows 95. You must run the game in a DOS based environment.
If you have problems doing this please consult SECTION#1: Making a Windows 95
Boot Disk.

List of contents:

        SECTION#1 - Making a Windows 95 Boot Disk
        SECTION#2 - General Problems
        SECTION#3 - Configuring your Sound Card
        SECTION#4 - Joystick Problems
        SECTION#5 - Video Problems
        SECTION#6 - Incompatibility Problems


SECTION#1 - Making a Windows 95 Boot Disk
=========================================

NOTE:  This method should not be used for machines that have SCSI peripherals
or that have compressed drives.  If you are unsure about either of these
points please contact your hardware vendor.

(1)	When in Windows 95, move down to the START button in the bottom left
corner of the screen.  Select from the PROGRAMS group the MS-DOS PROMPT.
The following message should be displayed

"Microsoft(r) Windows 95
	(c)Copyright Microsoft Corp 1981-1995
C:\WINDOWS>"


(2)	Insert a blank diskette into your machines 'A:' drive ensuring it is
not write protected.  Enter the following text.

	CD\	<ENTER>

	FORMAT A:/S	<ENTER>

You should then see the message

"Insert new diskette for drive A:
and press ENTER when ready..."

Pressing ENTER will start the formatting of the disk.  Upon completion of the
format the message

"Volume label (11 characters, ENTER for none)?"

will be shown.  Press ENTER to get past this and then enter 'N' in answer to
the question

"Format another (Y/N)?"


(3)	The machine should now be displaying the 'C:\>' prompt.  Now type the
following lines

	COPY CONFIG.SYS A:	<ENTER>

	COPY AUTOEXEC.BAT A:	<ENTER>

	A:			<ENTER>	

	EDIT AUTOEXEC.BAT	<ENTER>


(4)	Find in the text a line similar to the following

"C:\MOUSE\MOUSE.EXE"    (The mention of MOUSE being the important point)

and add the letters "LH " at the start of the line (if these letters are
already present proceed to step 5).  Using the above example the line would
now read

"LH C:\MOUSE\MOUSE.EXE"

N.B.  If this line, or one similar, is not present contact your hardware
vendor requesting a DOS based mouse driver for your system.


(5)	Next find the line that contains the word "MSCDEX.EXE", an example
being

"C:\WINDOWS\COMMAND\MSCDEX.EXE /D:MSCD000"

and again add the letters "LH " at the start of the line (if these letters
are already present proceed to step 6).  The example would now read

"LH C:\WINDOWS\COMMAND\MSCDEX.EXE /D:MSCD000"

The user is advised to note down the letters after the "/D:" section of the
above line (in this case it would be "MSCD000") for uses described later.

N.B.  If this line, or one similar, is not present contact your hardware
vendor requesting a DOS based CD ROM driver.


(6)	Now if the user has a SOUNDBLASTER sound card or compatible they
should find a line similar to the following:

"SET BLASTER=A220 I5 D1"


(7)	Next find a line similar to the one below

"PATH=C:\WINDOWS; C:\WINDOWS\COMMAND"

If this line is different or not present then edit or add it.


(8)	The user should now remove all the other lines in the file apart from
the four outlined. Therefore in our example the file would be as follows:

"PATH=C:\WINDOWS; C:\WINDOWS\COMMAND
LH C:\MOUSE\MOUSE.EXE
LH C:\WINDOWS\COMMAND\MSCDEX.EXE /D:MSCD000
SET BLASTER=A220 I5 D1"


(9)	Next hold down the 'ALT' key and press 'F' to bring up the FILE menu.
>From this select the SAVE option.  The file will now be saved to your
diskette.


(10)	Hold down 'ALT' and press 'F' once again, but this time select the
OPEN option.  A window will open asking for a file name, enter the following

A:\CONFIG.SYS

and press ENTER.  A new file will now be opened.  


(11)	Within the file the user should see the following line

"DEVICE=C:\WINDOWS\HIMEM.SYS"

If this line is not present it should be entered by the user at the very top
of the screen.


(12)	The user should next look for a line similar to the following

"DEVICE=C:\WINDOWS\EMM386.EXE RAM"

If this line is not present it should be entered below the previously
found/entered HIMEM.SYS line. If the line is differently worded to that above
it should be altered to match it.


(13)	Next find lines similar to the following

"DOS=HIGH, UMB
BUFFERS=15,0
FILES=30
LASTDRIVE=Z"

If these lines are not present or are differently worded alter them to match
the examples given.


(14)	The next thing the user needs to find is the line used to configure
the CD ROM drive.  In step 5 the user was asked to note down the text after
the "/D:" letters of a line in the AUTOEXEC.BAT file (in our example it was
MSCD000), and this is where it is needed.  Find the line that carries the
same text, for example

"DEVICE=C:\CDROM\SGIDECD.SYS /D:MSCD000"

This is the line used to control the CD ROM drive, after the word DEVICE the
user should add the word HIGH (with no spaces before or after the word) if it
is not already present.  Our example would therefore read

"DEVICEHIGH=C:\CDROM\SGIDECD.SYS /D:MSCD000"


(15)	The user should now remove all the lines that have not been covered
in steps 11-14.  Our example file would now look as follows.

"DEVICE=C:\WINDOWS\HIMEM.SYS
DEVICE=C:\WINDOWS\EMM386.EXE RAM
DOS=HIGH, UMB
BUFFERS=15,0
FILES=30
LASTDRIVE=Z
DEVICEHIGH=C:\CDROM\SGIDECD.SYS /D:MSCD000"


(16)	Next hold down the 'ALT' key and press 'F' to bring up the file menu,
from here select the SAVE option.  The file will now be written to the
diskette.  Once again hold down the 'ALT' key and press 'F', but this time
select the EXIT option.


(17)	The machine should now have returned to the "A:\>" prompt.  From here
type

	EXIT	<ENTER>

to return to Windows.


(18)	Save your work and close down all open applications, then shut down
Windows.  The message "IT IS NOW SAFE TO TURN OFF YOUR COMPUTER." should now
appear.  Now press the RESET button on the front of your machine (making sure
that the diskette is still in your A: drive).


(19)  	The machine will now restart, and should boot from your freshly
created disk.  Once loading has finished the machine should display the "A:\>"
prompt rather than the usual Windows 95 startup screen.
If your machine does display the Windows 95 screen as normal and not the DOS
prompt then contact your hardware vendor.


(20)	Follow the games loading instructions.  

This boot disk can be used with all DOS based games.  If you wish to return to
Windows simply remove the diskette from drive A: and restart the machine.

If your machine still has problems please contact your hardware vendor for
further information.


SECTION#2 - General Problems
============================

PROBLEM:
When I attempt to patch the message "Unable to patch 'C:\EF2000\conflict.cg'
file is different size should be 629380" is displayed.

Solution:

The EF2000 patch requires a fresh version of the game to be installed (i.e
one that has not been played). Therefore if this message is displayed (or
one similar to it) the EF2000 already installed should be deleted and the
program re-installed before the patch is run.


PROBLEM:
I get the error message '...requires at least 21,000,000 bytes to run...'.

Solution:
This error can be caused a number of ways:

a) You do not have sufficient hard drive space and therefore you need to      
   free up more.
b) You are using a disk compression program like Double Space, Drive      
   Space or Stacker etc..... (EF2000 does not support compression programs -    
   remove it).
c) You are trying to run the game in a Windows 95 DOS Shell, and if this   
   is the case you need to Shutdown from Windows into a DOS 
   environment. Read the games addendum or consult "SECTION#1 - Making a 
   Windows 95 boot disk".


PROBLEM:
I get a SPAWN error in diagnostics when checking my Sound Card.

Solution:
This can be a number of different things:

a) You haven't configured the MIDI and/or the DIGITAL AUDIO portions of your
   sound card. (See the section on Configuring your Soundcard).
b) Your soundcard isn't configured correctly in DOS, you will need to     
   contact the supplier of your machine and tell him you have a DOS   
   based game and that you require the sound card to be configured in    
   DOS. When they have done this - re-configure. 

PROBLEM:
When I run Diagnostics the majority of the tests fail including memory which
reads 0.

Solution:
You are running diagnostics in a Windows 95 DOS shell. YOU  MUST  SHUTDOWN
FROM WINDOWS 95 COMPLETELY. READ THE ADDENDUM.


PROBLEM:
When I try to run the game I get the message:
NO FILES IN N:\3DSHAPES\TFX\SH\ENVIRO\C\VERSION 1.40 BY COL.

Solution:
Type SET PATH= and press ENTER at your C:\ prompt

PROBLEM:
When I try to run the game it comes back with the message :
'No mouse driver found ....'

Solution:

Install a DOS based mouse driver. Ensure it has a version number of 8.9 or
above. (If your version is any older than this it wont work).
If you are unsure how to do this then follow these instructions:

Get to the 'C:\>' prompt and type :

dir mouse.* /s /p

and press enter.

This will search the whole of the hard drive for any programs called MOUSE.

Now, if you have a DOS based mouse driver installed there should be a file
called either: 'MOUSE.COM' or 'MOUSE.EXE'. If not then you need to contact
your supplier and ask them to send you one.
If you do then above the filename there should be a heading 'Directory of
C:\XXXXX'. Now if you type 'CD XXXXX' then enter, followed by 'MOUSE' and
then enter. You should see a message telling you your mouse is installed.
You can now load the game in the normal way.

PROBLEM:
When I test my video card in diagnostics the computer displays the lo-res
screen then after pressing a key the machine freezes or displays the message
'SPAWN ERROR'.

Solution:
Read the Video Problems section.

PROBLEM:
When you run the game you receive the error message:
 'Init: Sampleplayer please run config....'

Solved:
You have turned the music , speech and/or sound fx on and haven't configured
the sound card. Read the section on Configuring your sound card.
 
PROBLEM:
As the game is loading or loaded the program freezes or drops to DOS with an
'EMM Page Alloc failed..'

Solution:
This can be caused by two things either:
You don't have enough hard drive space to create a swap-file. 
(You should have about 30MB just to be on the safe side)
You are using disk compression. (Remove the compression).

PROBLEM:
On loading the game crashes with a 'CLUMP......' error message.

Solution:
Delete the files CLUMP_3.TXT and CLUMP_SS.TXT from the EF2000 directory. If
this doesn't work increase your BUFFERS= line in the CONFIG.SYS. If your
unsure how to actually do this contact us. This error can also be caused by
the 'Linear Frame Buffer'(for further information read the Video Card
problems).



SECTION#3 - Configuring your Sound Card
=======================================

To configure your sound card in EF2000, you must first get to the
'C:\EF2000>' prompt then type:

'CONFIG' followed by return.
>From here select the 2nd option down which is Preferences.
In here you will be presented with:
		Resolution
		Detail
		Control Method
		SFX*                         
		Speech*
		Music*
		Vr Headset
		Configure MIDI+Digital Audio Drivers *
		Configure Joystick

The options that are highlighted with an asterisk are the options we will use
to configure the sound in-game.

Selecting Sound Effects

If you want to have Sound Fx in-game move the cursor to the SFX option and
press enter. In here you will be presented with an Off/On option. Move the
cursor down to On and press enter.

Selecting Speech

Exactly the same as for Sound Effects except you move the cursor to Speech.

Selecting Music

When you select Music you are given 3 options, OFF,MIDI,CD.
MIDI is actual sound card music, and CD is music that is played directly from
the compact disk itself.
MIDI is more commonly used.


Selecting and configuring your Sound Card

The machines sound card should be setup before the program will run sound
correctly. Just because you have turned Sound FX, Music and Speech ON does not
mean you are going to get sound.
The sound card has to be determined by the system before you will hear
anything. So move the cursor to the 'Choose MIDI+Digital Audio Drivers'
and press Enter.
If everything went well you should now be presented with 5 options:

	Select and configure MIDI device.
	Select and configure digital audio driver.
 	No MIDI
	No Digital Audio
        Done

The first option should be highlighted so press enter. 
You should now be presented with a list of sound cards. The highlighted
sound-card is the one to select as it automatically highlights the card it
believes you have so just press enter.

Press enter again to accept 'Attempt to configure automatically' and at this
point you will either be successful or not. If you haven't then refer to the
problems section for suggestions on the problem. If you have then press enter
at the OK prompt and move your cursor to the next option down 'Select and
configure digital audio'. Follow the same procedure for the MIDI
configuration. If all's well then move down to Done, and then to down to
Save.


PROBLEMS WITH AN OPTI 7168V MD SOUNCARD AND WINDOWS 95

You need to make a shortcut from your windows desktop to your EF2000
directory in MS-DOS MODE. If you are unsure how to do this contact us.

PROBLEMS WITH GATEWAY 2000 MACHINES WITH ENSONIC SOUNDSCAPE SOUND CARDS WITH
WINDOWS95 INSTALLED.

You need to add some lines to the AUTOEXEC.BAT file in MS-DOS MODE.

C:\WINDOWS\MSCDEX /D:TSYCD3
SET SNDSCAPE=C:\SNDSCAPE
SET BLASTER=A220 IX DX T1 (Where X are the IRQ AND DMA chanels on your card)
PATH=%PATH%;C:\SNDSCAPE
SSINIT /I

If you are unsure how to do this contact us.


SECTION#4 - Joystick Problems
=============================

PROBLEM:
When trying to configure the joystick an ERROR NO JOYSTICK FOUND message
appears.

Solution:
Reconfigure the sound card. Also ensure the game port is enabled.

PROBLEM:
The plane just spins and or there is no joystick control.

Solution:
Access the joystick sensitivity scale and reduce or increase sensitvity.



SECTION#5 - Video Problems
==========================

Here are a number of solutions for people experiencing problems with their
video-cards. 

Here are the solutions (either or):

1. Try running 'UVCONFIG' within the EF2000 directory. Within there     
   you will notice a 'DISABLE LINEAR FRAME BUFFER' switch. If    
   you enable this followed by OK some video cards will respond to   
   this.

2. If not Install the Vesa driver that came with your video card (if you do                                
   not know the name of the driver you will have to contact your machine  
   supplier or the video card manufacturers).
   When you have done this you must re-install EF2000, and then delete     
   the  file 'UNIVBE.DRV' from the EF2000 directory. 
   (This is the most common problem)
	
3. If you have a Diamond Stealth Video card sometimes the default     
   monitor is set to something different from your actual monitor so to     
   rectify it, at the C: prompt type 'CD S64D'. After this type:
   'S64DMODE  MONITOR  -U'. When you have done this you must
   re-install the game again.

4. If you experience problems with Matrox Millennium video cards. 
   Type the following lines in your Matrox directory in DOS

        UVCONFIG S28 C2 M2048 D42 if you have a 2MB card or
        UVCONFIG S28 C2 M4096 D42 if you have a 4MB card  

     or if this doesn't work use these commands in the EF2000 directory

        UVCONFIG -S28 -C2 -M2048 -D42 if you have a 2MB card or
        UVCONFIG -S28 -C2 -M4096 -D42 if you have a 4MB card


PROBLEMS WITH DIAMOND EDGE V1.00

PROBLEM:
When I do the video card checks with the above graphics card installed,
the low-res test is fine but the hi-res test cause the machine to freeze.

Solution:
If you attempt to start the game, the program should run fine in both "lo" and
"hi" res modes.


PROBLEMS WITH #9-128 GRAPHICS ADAPTERS

PROBLEM:
Slow screen update considering the capabilities of the card.

Solution:
This is due to the card containing two graphics processors, the main 128
processor and a Cirrus Logic GD5424. The problem is that EF2000 detects
the GD5424 as the cards main processor which is very slow compared to the
main Imagine chip. We are sorry, but this can not be corrected.


SECTION#6 - Incompatibility Problems.
=====================================

VIGLEN MOUSE DRIVERS

All you need to do here is replace your mouse software with a Microsoft Mouse
driver version 9 or Higher.

MITSUMI CDROM DRIVERS VERSION 1.51

This driver needs to be down graded to version 1.35. Contact Mitsumi or your
Computer Supplier to obtain a copy.

MODEM IRQ SETTINGS

Tactcom cannot detect modems with an IRQ setting greater than 7. If you
wish to play Tactcom using a modem, please ensure that it is configured
with an IRQ setting of 7 or less.

If you have any further problems you can contact us;

By phone on     : 0161 288 7102
By fax on	: 0161 288 7098
Email		: helpline@gateweb.co.uk

Please include as much information about your problem and machine possible.

The Ocean helpline document was created by Rob Arnold, Simon Crawford,
Robin-Swan-Brown, Lee Clare, Gareth Betts and Marc Rogers.
