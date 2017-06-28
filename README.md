# keyboard_config

The config file can be imported, modified, and exported for flashing from [this link](https://input.club/configurator-md1-hacker/).

## How to flash

### Install the flashing program

`brew install dfu-util`

### Flash the exported bin file from the configurator

`dfu-util -D kiibohd.dfu.bin`
