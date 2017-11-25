# Yapi : Yeelight Java API
Yapi is an API that lets you control different Yeelight devices via Wi-Fi.

## Get Yapi
*In progress...*


## Usage / Example
Here is a simple example of how to use the API:
```java
// Instantiate your device (with its IP)
YeelightDevice device = new YeelightDevice("192.168.1.47");
// Switch on the device
device.setPower(true);
// Change device color
device.setRGB(255, 126, 0);
// Change device brightness
device.setBrightness(100);
```
For a complete overview of available commands, see the API documentation.
