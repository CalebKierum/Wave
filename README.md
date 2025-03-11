<p align="center">
    <img width="400" src="./Assets/Logo.png">
</p>

## Wave

[Check out the amazing work of jtrivedi](https://github.com/jtrivedi/Wave)! This is just a fork with a few changes I wanted to make since contributions to the original are closed. 

## Fixes

- SwiftUI demo no longer crashes due to reflection/mirroring of a SPI property "_velocity" which was replaced with an actual API in iOS 13.0 https://github.com/jtrivedi/Wave/issues/39
- SwiftUI demo no runs at a smooth 120 FPS by using a spring for the drag interaction as well https://github.com/jtrivedi/Wave/issues/39

## TODO
- Double check that DisplayLink is being told it does not need ProMotion when no active animations are happening.
- Support low power mode turning on and off by re-enabling pro motion on supported devices when they turn off low battery mode.
