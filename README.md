# SharkTracker

## Update firmware

1) Press and hold both the RESET/RST and MODE/SETUP buttons simultaneously.

2) Release only the RESET/RST button while continuing to hold the MODE/SETUP button.

3) Release the MODE/SETUP button once the device begins to blink yellow.

4) Now execute ```particle update```.

## To compile and flash the AssetTracker after `particle update`

Compile for the target architecture:
```particle compile electron --target 0.6.1```

Flash the firmware:
```particle flash --usb <file>```

To check what's happening, use the serial monitor:
```particle serial monitor```
