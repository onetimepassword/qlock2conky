# qlock2conky
qlocktwo for conky

### About

i came across the the following conky [configuration](http://mowgli-writes.deviantart.com/art/qlocktwo-conky-470067388) by mowgli for a [qlocktwo](www.qlocktwo.com/) and updated it for conky 1.10
which was previously adapted from original code by [aslamp](http://crunchbang.org/forums/viewtopic.php?id=4201)

the configuration, worked but conky complained: "Assuming it's in old syntax and attempting conversion." so i set out to update the configuration to work for conky 1.10.X

i updated the config section (yes to true, added =, corrected qoutes, removed # from colors, etc) and cleaned up some items in the conky.text(TEXT) script section to work properly as needed

### Install
place .conky in convenient location or replace default conky
```bash
$ mkdir -p ~/.config/conky
$ conky -C > ~/.config/conky/conky.conf
```
add conky script line so a dektop startup script, most DM/WM have an autostart script



### License
[MIT](https://opensource.org/licenses/MIT)

