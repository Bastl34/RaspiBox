# RaspiBox WIP (Raspberry Pi 4)
Manuals/Links for the RaspiBox

![Raspi Box](https://cdn.thingiverse.com/renders/ce/10/85/bb/08/bf6fef603f6cb21949797557faec39fd_preview_featured.jpg "Raspi Box")


# STL Download:
--> https://www.thingiverse.com/thing:3781308


# GPIO

`/boot/config.txt` 

```
#shutdown Switch
dtoverlay=gpio-shutdown,gpio_pin=3

#power led
dtoverlay=gpio-poweroff,gpiopin=21,active_low
```

# Monitor Sleep Mode
add `hdmi_blanking=1` to `/boot/config.txt`  

# Resolution

## 1440p
```
hdmi_group=2
hdmi_mode=87
hdmi_cvt=2560 1440 60 3 0 0 1
max_framebuffer_width=2560
max_framebuffer_height=1440
hdmi_pixel_freq_limit=400000000
```

# Slow SSD Fix (USB 3)
`https://www.raspberrypi.org/forums/viewtopic.php?f=28&t=245931`


# VS Code
`https://github.com/headmelted/codebuilds/issues/64`

# DRM Content
`https://blog.vpetkov.net/2019/07/12/netflix-and-spotify-on-a-raspberry-pi-4-with-latest-default-chromium/`
