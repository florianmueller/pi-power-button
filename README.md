# pi-power-button

Scripts used in our official [Raspberry Pi power button guide](https://howchoo.com/g/mwnlytk3zmm/how-to-add-a-power-button-to-your-raspberry-pi).

## Installation

1. [Connect to your Raspberry Pi via SSH](https://howchoo.com/g/mgi3mdnlnjq/how-to-log-in-to-a-raspberry-pi-via-ssh)
1. Clone this repo: `git clone https://github.com/florianmueller/pi-power-button.git`
1. Run the setup script: `./pi-power-button/script/install`

## Uninstallation

If you need to uninstall the power button script in order to use GPIO3 for another project or something:

1. Run the uninstall script: `./pi-power-button/script/uninstall`

## Hardware

At a minimum, you'll need a normally-open (NO) power button, some jumper wires, and a soldering iron. If you _don't_ have a soldering iron or don't feel like breaking it out, you can use [this prebuilt button](https://www.amazon.de/gp/product/B07C95MW3H/ref=ppx_yo_dt_b_asin_title_o05_s01?ie=UTF8&psc=1) instead.

Connect the power button to Pin 5 (SCL) and Pi 6 (GND) as shown in this diagram:

![Connection Diagram](https://raw.githubusercontent.com/Howchoo/pi-power-button/master/diagrams/pinout.png)
