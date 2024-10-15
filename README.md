lazy-backlight

Installation
------------

```
git clone https://github.com/arghyarp/lazy-backlight.git
cd lazy-backlight
sudo cp lazy-backlight /usr/bin/
lazy-backlight allowusers
```


Usage
-----

This repo contains a bash script `lazy-backlight` to control keyboard backlight state
and also an Upstart script `lazy-backlight.conf` to allow regular users to do it.

`lazy-backlight` accepts following keys:

```
$ lazy-backlight next   # cycle keyboard brightness
$ lazy-backlight up     # make backlight one step brighter
$ lazy-backlight down   # make backlight one step darker
$ lazy-backlight max    # maximum level backlight
$ lazy-backlight min    # minimum level backlight
$ lazy-backlight off    # turn backlight off
$ lazy-backlight 2      # you can also tell a specific level
$ lazy-backlight show   # this shows current backlight level
```

