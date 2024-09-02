# drc-test
A Wii U homebrew application to test the DRC and read/write some hidden values.

This fork was updated and built using the latest version of wut, and is compatible with Aroma. The original version is meant for Tiramisu and legacy CFWs.

Aroma and Tiramisu/legacy versions are available for download. If you use Aroma and Tiramisu, you may download both versions.

## Features for testing
- Buttons/Joysticks
- Screen/Touchscreen
- Gyroscope
- Accelerometer
- Direction
- Angle
- Magnetometer
- Volume
- Battery
- Vibration
- Gamepad Sensor Bar
- Gamepad BASE

## Usage
### Aroma
Download `drctest.wuhb` from [https://github.com/theawesomecoder61/drc-test/releases/latest] and place it on your Wii U SD card at `sd:/wiiu/apps/drctest/`. It will appear on your Wii U home screen.

### Tiramisu and legacy CFWs
Download `drctest.rpx` from [https://github.com/theawesomecoder61/drc-test/releases/latest] and place it on your Wii U SD card at `sd:/wiiu/apps/drctest/`. It will appear in the Homebrew Launcher.

## Compiling
On Linux or WSL, download and install devkitPro's wut package: [https://github.com/devkitPro/wut] and follow the initial instructions for compiling projects (No extra libraries are needed), then clone the repository, unzip the files and write on the command line:
```
cd drc-test-master
make
```

## Credit
- Pokes303: drc-test