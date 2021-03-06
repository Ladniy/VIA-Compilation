# VIA Compilation
This is repository of compilation files for VIA configurator. Only for [Jiran keyboard.](https://github.com/Ladniy/jiran-breakoff) 

Main JSON file, that you need for VIA configurator to work:
[Jiran Main File](https://github.com/Ladniy/VIA-Compilation/blob/master/Jiran%20Main%20File.json)

[My own Jiran layout](https://github.com/Ladniy/VIA-Compilation/tree/master/Ladniy)

## How work with VIA

First of all you need to flash your Jiran keyboard with correct firmware version (use [QMK toolbox](https://github.com/qmk/qmk_toolbox/releases)).

Flash this [HEX file](https://github.com/Ladniy/VIA-Compilation/blob/master/jiran_rev1_via.hex) if you got revision with single color LEDs

Flash this [HEX file](https://github.com/Ladniy/VIA-Compilation/blob/master/jiran_rev2_via.hex) it you got revision with RGB LEDs

After flashing you can start configure VIA:

* [Download VIA](https://github.com/the-via/releases/releases/tag/v1.3.1)
* [Download Main File](https://github.com/Ladniy/VIA-Compilation/blob/master/Jiran%20Main%20File.json)
* Open main file into VIA:

  * Open VIA
  * Open main file by hotkeys (Ctrl + O) or menu in right upper corner of VIA window

After all these actions you will see default Jiran layout:

<img src="https://i.imgur.com/33ByS31.png" data-canonical-src="Render" height="450"/>

Now you can configure your layout as you want.

## How to publish your layout here

For create your own layout and publish it here you need:

* Fork this repository, then create your own folder with your nickname
* Open VIA and configure your own layout
* Save layout in a early created folder and name it `jiran_<your_nickname>.json`
* Make some screenshots of your layout and upload them to [imgur.com](https://imgur.com/)
* Create and fill README.md file:
  * Write little discription of your layout
  * Insert screenshots there

After all of this action you can create pull request.

[**Example of VIA catalog**](https://github.com/Ladniy/VIA-Compilation/tree/master/Example)
