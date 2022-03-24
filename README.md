# anduril2

Fork of ToyKeeper's Anduril 2 flashlight firmware

[Launchpad repository](https://code.launchpad.net/~toykeeper/flashlight-firmware/anduril2)

## Local changes

Sunset timers from Candle mode and On mode go straight to lockout mode on expiry

Disable the blink when using 3 clicks from locked to go to off

## New configuration options

If BLINK\_USING\_RGB is set then blink_digit() will use the Aux RGB LEDs instead of the main emitters

RGB\_BLINK\_COLOR defines the color to use for this (0b00BBGGRR)
