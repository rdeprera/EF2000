EF2000 V2.0 
(c) Copyright Digital Image Design Ltd., 1997

This document provides information for EF2000 V2.0 which
is not included in the documentation.

For Technical Support call: 408 289 1411

CONTENTS

PART A	Windows 95 Version
PART B	DOS Version
PART C	Graphics Plus (Rendition and 3Dfx) Version



    ========================================================================================================
A - EF2000 V2.0 for Windows 95
    ========================================================================================================

A1.  SETUP ISSUES
A1.1 What has been altered in your machine configuration?
A1.2 DirectX compatibility issues
A1.2.1 Quickrez
A1.2.2 Video refresh rates
A1.2.3 General compatibility
A1.3 Uninstalling EF2000 V2.0 (Win 95)

A2.  SYSTEM REQUIREMENTS
A2.1 Minimum specification.
A2.2 Optimal specification.

A3.  GAME USAGE
A3.1 Game Configuration
A3.2 On-line help
A3.3 Performance Tuning
A3.4 Windows-Specific Keys
A3.5 Windows Taskbar
A3.6 Windows Shutdown

A4.  NETWORK PLAY
A4.1 Novell Netware Requester
A4.2 Uninstallation of Novell Netware 32-bit Requester Client
A4.3 Network play
A4.4 Leaving a network game
A4.5 TEN Problems

A5. Mission debriefs on modem-linked machines

A6. Some additional notes from Ocean QA department

A7. Frequently asked questions
--

A1. SETUP ISSUES

A1.1 What has been altered in your machine configuration?

Due to the large performance requirements of all games it was necessary
to ensure the installation of the Microsoft Games API.  Also known as DirectX,
this set of system utilities has also added functionality to the standard Windows '95
configuration

A1.2 DirectX compatibility issues

Microsoft's Games API supports the most popular video and sound cards.
Certain problems have been noted with some of the lesser-known cards
particularly video cards.  Some of these issues can be resolved simply.

A1.2.1 Quickrez
A free, unsupported, utility has been distributed by Microsoft.
This utility, named "Quickrez", allows the dynamic alteration of screen resolution.
This program is NOT compatible with the version of the Microsoft Games API
that we require (DirectX 3.0).  All is not lost, however, as DirectX 3.0 has
extended the functionality of the Display Settings tab control.
Therefore uninstall Quickrez and then:

i)     Open the display settings tabbed control (Via Control Panel)
ii)    Select the "Settings" page
iii)   Ensure the "Show settings icon on Taskbar" checkbox is ticked
iv)    Click "OK" to close the settings and a Quickrez-like icon will
        be displayed on the Taskbar.

A1.2.2 Video refresh rates
The "Optimal" Refresh rate (under the Advanced Display options) is NOT compatible
with full-screen graphics modes of 640x400 with certain video cards.  This setting
is usually "Adapter Default" so should not be changed unless you are sure it is compatible.

A1.2.3 General compatibility
Being reliant on the underlying Microsoft Games API we are assured that any
compatibility problems should be directed to obtaining updated device drivers
from the relevant hardware manufacturer.

A1.3 Uninstalling EF2000 V2.0 (Win 95)
Select the "Add/Remove Programs" from the Control Panel and highlight
the EF2000 V2.0 (Win 95) component before clicking the "Add/Remove" button.
All configuration settings and campaign features are removed.
See section 4.2 "Uninstallation of Novell Netware 32-bit Requester" for
more information if you have installed this component.

A2.0 SYSTEM REQUIREMENTS

A2.1 Minimum specification.

EF2000 V2.0 (Win 95) requires at least the following system configuration:

CPU:          	Pentium P75 or equivalent
RAM:          	16MB.
HD SPACE:  	20MB free (excluding Windows swap space).
CD:          	2 x CD-ROM drive.
SOUND:          Sound Blaster or Windows compatible card.
MOUSE:          Microsoft Mouse or other Windows '95 compatible device

A2.2 Optimal specification.

CPU:          	Pentium P120 or higher
RAM:          	32MB.
HD SPACE:       70MB free (excluding Windows swap space).
CD:          	4 x CD-ROM drive.
SOUND:          Sound Blaster AWE32 card
MOUSE:          Microsoft Mouse or other Windows '95 compatible device

For multi-player:
MODEM:          2 players over minimum 9,600 BPS modem.
               	A 28,800 modem is recommended.
NETWORK:      	2-8 players over Windows compliant network.

A3.   GAME PERFORMANCE

A3.1 Game Configuration
During the installation, several in-game options are considered, such as music/sound,
detail levels etc.  These can also be configured via the in-game options screen.
The only exception to this is the minimal/full install option. 

A3.2 On-line help

A major addition to EF2000 V2.0 (Win 95) is the context-sensitive On-line help.  This may be
used by pressing ALT+F1 on your keyboard.  Many hours of thought have gone into this to make 
it an indispensable guide to flying tactics/hints and tips etc.  Use it - it helps...

A3.3 Performance Tuning

Because Windows is a multitasking environment it is easy to cause a slowdown in
applications when using this facility. Therefore several things can be done to ensure
EF2000 V2.0 (Win 95) plays at its best on your machine:

i)   Try not to run any other programs - i.e. playing EF2000 V2.0 (Win 95) whilst
     using a database doesn't help either program.
ii)  Ensure there are no device conflicts.  Use the System Properties
     tabbed control (System icon in Control Panel) - to ensure there
     are no yellow exclamation marks on the Device Manager page.
     If there are then you may be suffering a general performance loss
iii) Ensure that your system is configured for optimal performance
     (Again this information resides in the System Properties only
     this time under the Performance tab).
iv)  Aim towards our optimal specification machine.
v)   Run the game full-screen (ALT+Enter) - this means Windows only
      needs to update our screen.
vi)  To help disk access speed on machines with 32Mb+ of RAM then
      the size of the internal disk cache in Windows '95 can be increased by:
     Opening the System Properties tabbed control (as described above)
     Click on the "Performance" tab
     Click on the "File System" button
     Change the typical role of the machine to "Network Server"
     Click OK until exit of this control

A3.4 Windows-Specific Keys

The left ALT key is reserved for Windows 95 functions. ALT-TAB is used for task switching
and ALT-RETURN is used for full-screen switching. As EF2000 V2.0 (Win 95) uses a high-resolution
GUI there may be some switching of screen resolutions at points in the game. If you
find that the display freezes for any length of time then pressing ALT-RETURN can
sometimes rectify this problem. Likewise, the right mouse button is usually reserved
for windows functions.

In EF2000 V2.0 (Win 95), the right mouse button is used for a number
of things. If you experience problems (such as a constantly zoom-in, zoom-out cockpit)
then clicking the right mouse button should rectify the problem. Use of the keypad
for outside views will require NUMLOCK being turned off

A3.5 Windows Taskbar

On full screen setting in high resolution the taskbar may still be visible.
To prevent this happening you should right-click on the task bar and select "properties"
from the menu. This will bring up a Taskbar properties window. On the options
tab, please deselect the "always on top" option.

A3.6 Windows Shutdown
If midi music is selected in EF2000 V2.0 (Win 95) the music may carry on for a few seconds
after the game has been shut down. Windows 95 should not be shut down until after
the music has stopped.

A4.  NETWORK PLAY

A4.1 Novell Netware 32-bit Requester

The Novell Netware 32-bit requester is used for its greater efficiency.  If you intend
to play the network version of EF2000 V2.0 (Win 95), you should install the 32-bit requester.

A4.2 Uninstallation of Novell Netware 32-bit Requester Client

Client 32 is a separate program and will not be deleted by uninstalling
EF2000 V2.0 (Win 95). If you wish to uninstall the program then you must
delete the directory it is installed to. Please consult your network
supervisor before attempting to remove any components of the Networking software.

A4.3 Network Play

When playing EF2000 V2.0 (Win 95) over a network, all the players must have
the "currently linked players" screen visible before the server selects a mission.

As a result of the upgrades made to the networking and campaign in EF2000 V2.0 (Win 95),
It is recommended that a maximum of four players engage in networked
campaign missions. This is due to the complexity of the information that is
required by all the machines. The option for eight players is still available
but the players may experience occasional problems due to loss of information
between computers on a network.

A4.4 Leaving a network game

If any of the players linked to a game in network mode decide to leave the game then
the game must be restarted. All players should exit the mission they are on and the
server machine must click on the "Restart Network" button on the multi-player screen.

A4.5 Ten Problems

If you encounter problems connecting to or playing in the TEN environment then refer
to the Customer Service section in the TEN help file or contact the Total Entertainment
Network (TEN) on 1-800-8040-TEN. 

A5. Mission debriefs on modem-linked machines

On modem-linked games you may experience inaccuracies between the game and the debriefs.
This is due to the data transfer rate being low. A faster baud rate will improve the
situation if it is available on both modems being used.

A6. Some additional notes from the QA department

If playing in low resolution you may encounter a problem whilst loading missions
in full screen. The error reported is:
"Superw has performed an illegal operation and will be shut down."
If this is the case then load the mission in a window to rectify this problem

Paradise 64 Video card
When using the Paradise 64 video card, users may find that there are two
cursors present whilst they are on menu screens. This does not cause any
gameplay problems.

Problems uninstalling game.
If the user encounters any problems uninstalling the game via add/remove
programs, they should manually remove any parts of EF2000 V2.0 (Win 95) that are
remaining. The instructions for deleting folders or deleting programs
from the START menu can be found in the Windows 95 HELP files.
NB Do not attempt to manually remove the files if 
you are in any way uncertain of what you are doing.

DirectX
When DirectX is installed by EF2000 V2.0 (Win 95), users of some graphics cards
that possess 'Powerdesk' utilities to change the machines display
properties (E.g. Matrox Millennium video card) will find that the
Powerdesk will have been removed. This will not affect the performance
of the card and the user should still be able to set all the previously
available screen resolutions and color settings.

Multi CD systems.
If the game is being played on a machine with a multi-CD system then in
order for the game to play with CD music the user will have to ensure that
the EF2000 V2.0 CD is the first one in the disk caddie.

Installation
Whilst the user is installing EF2000 V2.0 (Win 95), it is recommended that they
do not minimize the window.

EF2000.$$$
Once the user has uninstalled the game, they may find that a file named
EF2000.$$$ is left behind in the root of C:. If this is the case then
the user should manually remove the file.

A7. Frequently asked questions

1) 8-bit and mono soundcards

attempting to play EF2000 V2.0 (win 95) with an 8-bit or mono card 
will cause the error;

 INIT SAMPLE PLAYER LINE 332 DSERR_BAD FORMAT
 
The game will not run unless you disable sound, EF2000
is coded to run in stereo. Unfortunately to only way to fix
this problem is to upgrade to a stereo soundcard.

2) CD-ROM driver conflict

Some CD-ROM drivers conflict with EF2000's
built-in CD player causing the error;

 BAD TRACKNO : 1

This is not a problem with the CD and can be solved by 
adding the word " REM " before all lines in your 
config.sys that are to do with your CD-ROM driver;
for example:

device=c:\timcd.SYS /D:MSCD001 

would become

Rem device=c:\timcd.SYS /D:MSCD001 

Remember to save and reboot after making any changes.


3) CSPMAN.DLL library problem

Some users may experience problems with the Cspman.dll
file. If this occurs then the following error message
will be displayed:

Msgsrv 32 error has occurred in the "cspman.dll" file.

Windows usually crashes after this error message.
This problem can be fixed by reinstalling your sound
drivers from the DirectX folder on the EF2000 CD.


4) Windows NT4.0 Compatibility

EF2000 does have some compatibility problems
with NT4.0, these can be resolved by copying over 
the Directx folder from the EF2000 CD and 
adding the folder you have copied it to, to your path
statement, after rebooting EF2000 works fine.



    =================================================================================================
B - EF2000 V2.0 for DOS.
    =================================================================================================

B1. Installation
B2. Network games
B3. Configuration
B4. Mission debriefs
B5. Ocean Helpline's EF2000 and EF2000 V2.0 (DOS) troubleshooting guide
B6. Frequently asked questions

B1. Installation

The installation procedure is straight forward. Please ensure that the files 
setting in your config.sys is set higher than 25 and that the buffers setting 
is more than 35.

B2. Network games

As a result of the upgrades made to the networking and campaign in EF2000 V2.0 (DOS),
It is recommended that a maximum of four players engage in networked
campaign missions. This is due to the complexity of the information that is
required by all the machines. The option for eight players is still available
but the players may experience occasional problems due to loss of information
between computers on a network.

If any of the players linked to a game in network mode decide to leave the 
game then the game must be restarted. All players should exit the mission 
they are on and the server machine must click on the "Restart Network" button 
on the multi-player screen.

B3. Configuration

If you change the setup of the sound on EF2000 V2.0 (DOS), it is advisable
to reconfigure the joystick. This is because the joystick readings are different
with sound configured.

B4. Mission debriefs

On modem-linked games you may experience inaccuracies between the game and the
debriefs. This is due to the data transfer rate being low. A faster baud rate
will improve the situation if it is available on both modems being used. 

B5. Ocean Helpline's EF2000 EF2000 V2.0 (DOS) Troubleshooting guide.
    
List of contents:

	Section #1 - General Problems
	Section #2 - Configuring your Sound Card
	Section #3 - Joystick Problems
	Section #4 - Video Problems
	Section #5 - Incompatibility Problems


Section#1 - General Problems
            ----------------


PROBLEM:
I get the error message '...requires at least 21,000,000 bytes to run...'.

Solution:
This error can be caused a number of ways:

a) You do not have sufficient hard drive space and therefore you need to      
   free up more.
b) You are using a disk compression program like Double Space, Drive      
   Space or Stacker etc..... (EF2000 does not support compression programs -    
   remove it).
c) You are trying to run the DOS game in a Windows 95 DOS Shell, and if this   
   is the case you need to Shutdown from Windows into a DOS  environment. 
   Alternatively, Install the Windows 95 version of EF2000 V2.0


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
FROM WINDOWS 95 COMPLETELY.


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

Solution:
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
unsure how to actually do this contact us.



Section#2 - Configuring your Sound Card
            ---------------------------


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


Section#3 - Joystick Problems
            -----------------


PROBLEM:
When trying to configure the joystick an ERROR NO JOYSTICK FOUND message
appears.

Solution:
Reconfigure the sound card. Also ensure the game port is enabled.

PROBLEM:
The plane just spins and or there is no joystick control.

Solution:
Access the joystick sensitivity scale and reduce or increase sensitivity. Pressing ALT-C In-game
will recentralize the controls



Section#4 - Video Problems
            --------------


Here are a number of solutions for people experiencing problems with their
video-cards. 


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


SECTION#5 - Incompatibility Problems.
            -------------------------


VIGLEN MOUSE DRIVERS

All you need to do here is replace your mouse software with a Microsoft Mouse
driver version 9 or Higher.

MITSUMI CDROM DRIVERS VERSION 1.51

This driver needs to be down graded to version 1.35. Contact Mitsumi or your
Computer Supplier to obtain a copy.

MODEM IRQ SETTINGS

EF2000 V2.0 (DOS) cannot detect modems with an IRQ setting greater than 7. If you
wish to play EF2000 V2.0 (DOS) using a modem, please ensure that it is configured
with an IRQ setting of 7 or less.

If you have any further problems you can contact the Ocean helpline;

By phone on     : 408 289 1411


Please include as much information about your problem and machine possible.

The Ocean helpline document was created by Rob Arnold, Simon Crawford,
Robin-Swan-Brown, Lee Clare, Gareth Betts and Marc Rogers.

B6. Frequently asked questions

1)  d:\gui.par

      Can be fixed by increasing files and buffers in your config.sys file to 30 or more 

2) Tseng et6000 (vision magic bios)
      
      If you have this graphics card are getting a blank screen or the error message: 'set rez unable to set                                        
      vesa mode' this can be fixed by going to videologics home page and download the 'patch216.zip'                     
      file for their grafixstar600 series of SVGA cards, this updates your BIOS and can be added to your            
      autoexec.bat

3) N:\3D Shapes......

      If you get this error when you are installing EF2000 or are playing the game you will have to 
      enter this line into your config.sys file to fix it:

                 SHELL=C:\COMMAND.COM /P /E:2048 

4)  Screen bending / distortion.
      
      This caused by the auto-detecting software we use to configure graphics cards but some problems 
      have been occurring like black lines at the top and bottom of the screen. These problems can be  
      fixed by downloading the display doctor from sci-tech at www.scitechsoft.com

5) Modem problems.

      I you find that you are having problems with modem play in EF2000 make sure that you have the  
      IRQ set to less than seven.  Also check that your com ports are set to these addresses:

      COM 1 is 3F8
      COM 2 is 2F8
      COM 3 is 3E8
      COM 4 is 2E8



    ========================================================================================================
C - EF2000 V2.0 GRAPHICS PLUS.
    ========================================================================================================

Configuring a Windows 95 DOS box.
---------------------------------

The Setup program normally installs EF2000 V2.0 (Graphics plus) and configures
the game to run from the desktop. Should any problems be encountered the procedure
detailed below should be followed.

Click with your right mouse button on an empty area of your Windows 95 desktop.

From the menu, select 'New'.

From the submenu, select 'Shortcut'.

In the 'Command line' edit box, type the drive, path, and filename of the games batch file.
e.g. C:\EF2000\EF2000.BAT

Type a name for the shortcut you are creating. e.g. Graphics Plus.

Now select an icon for the shortcut.

The shortcut will now be on your desktop.

Click with your right mouse button on the newly created shortcut.

Select 'Properties' from the menu.

On the 'Program' tab page :

   Ensure that the 'Working' edit box specifies the drive and path in which the game files
   are located. e.g. C:\EF2000

   Put a check in the 'Close on exit' checkbox. Should you encounter any problems running
   the game, this can be unchecked so that any errors returned to the DOS box can be
   reported.

On the 'Memory' tab page :

   Set 'Initial environment' to 2048.

   Put a check in the 'Protected' checkbox.

   Set 'Expanded (EMS) memory' to None.

   Set 'Extended (XMS) memory' to None.

   Put a check in the 'Uses HMA' checkbox.

   Set 'MS-DOS protected-mode (DPMI) memory' to 65535.

On the 'Screen' tab page :

   Select the 'Full-screen' radio button.

   Uncheck the 'Dynamic memory allocation' checkbox.

On the 'Misc' tab page :

   Uncheck the 'Allow screen saver' checkbox.

   Move the 'Idle sensitivity' slider to low.   

   Uncheck all of 'Windows shortcut keys' checkboxes.
   
Finally, click on 'OK'. The shortcut is now configured and can be run
by double clicking on it.


General.
--------

ALT F7 - Decrease gamma correction
ALT F8 - increase gamma correction


3Dfx based cards.
-----------------

Although this game is run from Windows 95, it is not a native application. This means that
GLIDE.DLL and SST1INIT.DLL (3Dfx's proprietary Windows 95 DLLs) are not used and have no
bearing whatsoever on our product's performance.

When running on some systems, the game's sound effects may be heard to stutter. 
Should you encounter this problem, the 3Dfx wait should be increased as per keys below until
the sound resumes normal operation. The default is to not wait at all. 

ALT -    Decrease 3Dfx wait. 
ALT +    Increase 3Dfx wait.

It should be noted that the above keys must be pressed repeatedly - they do not auto repeat.

If the above procedure does not produce the result you require then the addition of the line:

   set sst_wait_on_vsync_enable=0

in your autoexec.bat will solve the sound stutter. It should be noted that this method
may produce some visual problems such as "tearing".

After installation of the 3Dfx version windows may tell you that the program is better if
it is run under DOS, If presented with the option, click on NO. The accelerated
versions of EF2000 will only work reliably when run in a Win95-DOS environment

Rendition V1000 based cards.
----------------------------

The Rendition V1000 version of the game utilizes the Windows 95 display drivers.
Some older versions of these drivers fail when used by a DOS program. Always ensure that
the most recent drivers are installed and selected.

ALT F10 
Cycle gamma correction mode. Initially gamma correction affects red, green and 
blue simultaneously. By changing the gamma correction mode, subsequent presses of 
ALT F7 and ALT F8 can be made to affect red, green and blue components individually.
The available modes are RGB(simultaneously), R(individually), G(individually), and
B(individually).

ALT F9
Toggle shape anti-aliasing on/off. This results in mobile shapes such as planes and tanks
having their external smoothed.


PLEASE NOTE:
If you are using the rendition version of EF2000 V2.0, Installation of DirectX 3
may cause the error:
"Couldn't open Verite card. Error 50 code 1"
when trying to play the game. This problem is rectified by installing the Rendition
video drivers again.

