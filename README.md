# Evoluent-wayland-fix

`99-evoluent.hwdb` goes in /etc/udev/hwdb.d/

With `# evtest`...

Evoluent Mouse info:
```
Input device ID: bus 0x3 vendor 0x1a7c product 0x191 version 0x100
Input device name: "SONiX Evoluent VerticalMouse 4"
Supported events:
  Event type 0 (EV_SYN)
  Event type 1 (EV_KEY)
    Event code 272 (BTN_LEFT)
    Event code 273 (BTN_RIGHT)
    Event code 274 (BTN_MIDDLE)
    Event code 275 (BTN_SIDE)
    Event code 277 (BTN_FORWARD)
  Event type 2 (EV_REL)
    Event code 0 (REL_X)
    Event code 1 (REL_Y)
    Event code 6 (REL_HWHEEL)
    Event code 8 (REL_WHEEL)
    Event code 11 (REL_WHEEL_HI_RES)
    Event code 12 (REL_HWHEEL_HI_RES)
  Event type 4 (EV_MSC)
    Event code 4 (MSC_SCAN)
```

value 90001 = BTN_LEFT 

value 90002 = BTN_RIGHT 

value 90003 = BTN_MIDDLE 

value 90004 = BTN_SIDE [backward] 

value 90005 = BTN_EXTRA [mousewheel] 

value 90006 = BTN_FORWARD

