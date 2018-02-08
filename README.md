[![HCPA-5V-U3](HCPA-5V-U3_I2C.png)](https://store.ncd.io/product/hcpa-5v-u3-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/).

# HCPA-5V-U3

This I2C Mini Module provides an ideal solution for high accuracy humidity sensing.These capacitive polymer sensor chips are individually calibrated and tested. HumiChip® performs ±2% from 20% to 80%RH (±3% over entire humidity range) packaged in a convenient I2C Mini Module.
This Device is available from www.ncd.io

[SKU: HCPA-5V-U3]

(https://store.ncd.io/product/hcpa-5v-u3-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface HCPA-5V-U3 humidity and temperature sensor With Raspberry Pi :

1. <a href="https://store.ncd.io/product/hcpa-5v-u3-humidity-and-temperature-sensor-%C2%B12rh-%C2%B10-3c-i2c-mini-module/">HCPA-5V-U3 humidity and temperature Sensor</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>

3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python

Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python HCPA_5V_U3.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
