# BTHomeV2-ESP32-example
An example BTHome v2 example with a presence and a count sensor

# Notice it's currently under development

This is an example for a DIY [BTHome v2](https://bthome.io/) sensor.

The original code is from: https://github.com/TheDigital1/ESP32_BTHome

The header file contains human readable variables for the hex Object ids.

Note: yes = true (0x01), no = false (0x00) for the binary sensors.

For number states there is the `intToLittleEndianHexString` method to use like in the temperature example.

The length for the messages is automatically generated.

Read the comments in the code for more info on what can be changed and for the object ids consider using the variables from BTHome.h instead.

Unfortunately the encryption documentation is not clear to me and can't yet implement it.
