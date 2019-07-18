# RaspiBox WIP
Manuals for the RaspiBox


# GPIO

`/boot/config.txt` 

```
#shutdown Switch
dtoverlay=gpio-shutdown,gpio_pin=3

#power led
dtoverlay=gpio-poweroff,gpiopin=21,active_low
```
