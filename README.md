**DMX-Hue BLE - OLA trigger config to control Philips Hue BLE lights with DMX (Art-Net, sACN or via DMX input) - work in progress** 

Like others I can control Philips Hue BLE bulbs using nRF Connect on Android but I still have some problems with gatttool on Raspbian.
I can pair the bulb though.

`gatttool -t random -b [MAC] --char-write-req --handle=0x0027 --value=01`


[https://github.com/CANDY-LINE/node-red-contrib-generic-ble/issues/30](https://github.com/CANDY-LINE/node-red-contrib-generic-ble/issues/30)  
[https://github.com/Mic92/hue-ble-ctl](https://github.com/Mic92/hue-ble-ctl)  
[https://www.reddit.com/r/Hue/comments/eq0y3y/philips_hue_bluetooth_developer_documentation](https://www.reddit.com/r/Hue/comments/eq0y3y/philips_hue_bluetooth_developer_documentation)  
[https://gist.github.com/shinyquagsire23/f7907fdf6b470200702e75a30135caf3](https://gist.github.com/shinyquagsire23/f7907fdf6b470200702e75a30135caf3)
