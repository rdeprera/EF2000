# (DID) EF2000 2.0 TACTCOM - DOS

Game data for EF2000 2.0 TACTCOM, a popular **flight simulation game** from 90's for the **Eurofighter 2000 *Typhoon***.  
![EF2000 Screenshots](https://user-images.githubusercontent.com/4818168/173661304-fd761db0-5fa1-4cef-ba77-2dc6ff66c1d9.gif)  
> created by the legendary company [DID](https://en.wikipedia.org/wiki/Digital_Image_Design)  
> **Abandonware** since :question:


## Requirements

- [DOSBox](https://www.dosbox.com/) or [DOSBox-X](https://dosbox-x.com/)

### Optional 3dfx Support for DOSBox-x
- nGlide (windows) or OpenGlide (macOs and GNU/Linux). See https://dosbox-x.com/wiki/Guide%3ASetting-up-3dfx-Voodoo-in-DOSBox‐X

## DOSBox :rage1:

- `git clone --depth 1 -b dosbox https://github.com/rdeprera/EF2000.git`
- Game configurations: `dosbox -conf dosBox_EF2000.conf CONF.EXE`
- Play EF2000: `dosbox -conf dosBox_EF2000.conf EF2000.BAT`

`dosBox_EF2000.conf` is a [**DOSBox** configuration](https://www.dosbox.com/wiki/Dosbox.conf) file optimizide to run the this game.


## DOSBox-X :rage2:

- `git clone --depth 1 -b dosbox-x https://github.com/rdeprera/EF2000.git`
- Game configurations: `dosbox -conf dosBox_EF2000.conf CONF.EXE`
- Play EF2000: `dosbox -conf dosBox-x_EF2000.conf EF2000.BAT`

`dosBox-x_EF2000.conf` is a [**DOSBox-X** configuration](https://dosbox-x.com/wiki/) file optimizide to run the this game.
