**The Digital Temperature & Relative Humidity (RH) Sensor** is a device used to measure air temperature and relative humidity. It is easy to use and provides accurate readings. The module is built with a sensor from the SHT3x series (such as SHT30 or SHT31), which is widely used in environmental science, smart home systems, and various automated monitoring applications.

## This sensor is suitable for:
- Smart home and HVAC systems
- Greenhouse and agriculture monitoring
- Weather stations
- Classroom science experiments
- Environmental data logging

## **Specifications**
|Parameter|Value|
|-|-|
|**Model**|SHT30 Digital Temp & RH sensor|
|**Temperature Range**|–40 °C to +125 °C|
|**Temperature Accuracy**|±0.2 °C|
|**Humidity Range**|0 – 100 % RH|
|**Humidity Accuracy**|±2 % RH|
|**Supply Voltage**|2.4 – 5.5 V|
|**Interface**| I²C (2-wire communication)|

## Block Code Reference
| <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%204.png?raw=true" width="160" /> | Use this block to read the temperature from the sensor in degrees Celsius (°C). |
|-|-|
| <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%205.png?raw=true" width="150" /> | **Use this block to read the relative humidity from the sensor in percent (%).** |

<img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/Example%20code.png?raw=true" width="250" />

[**Download the working code here**](https://code.gogoboard.org/#/program/8fd04527-d891-4830-b3bf-3985969c1ab1)

## **Required Equipment**
| Equipment | Image |
|-|-|
| Digital Temp & RH Sensor | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/digital%20temperature.png?raw=true" width="200" /> |
| **Grove cable** | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/only%20grove%20(test).png?raw=true" width="200" /> |
| **Computer or Tablet** | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/computer%20or%20tablet.png?raw=true" width="200" /> |
| **GoGo Board and USB-C cable** | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/gogoboard%20and%20usb.png?raw=true" width="200" /> |

## **How to use**
**1. Connect the GoGo Board**
- Connect the GoGo Board to your computer or tablet via USB-C cable or Wi-Fi
<img src="https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true" width="500" />


**2. Connect the Temp & RH Sensor**
- Connect the Temp & RH Sensor to a Grove cable, then plug the cable into the black Add-ons port on the GoGo Board.

| <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH.gif?raw=true" width="400" /> | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/digital%20temperature%20with%20board%20(new%20version).png?raw=true" width="400" /> |
|-|-|


## Getting Started with the Digital Temperature & Relative Humidity Sensor on GoGo Code 

**1. Visit the GoGo Code website:**
- Go to [GoGo Code](https://code.gogoboard.org/#/program) to start programming and controlling your device.

**2. Add the Digital Temperature & Relative Humidity Sensor extension:**
- Click on the **Add Extension** category

| <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH.gif?raw=true" width="400" /> | <img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/digital%20temperature%20with%20board%20(new%20version).png?raw=true" width="400" /> |
|-|-|

- Select **Official**, then click the **[ Multi ] - Temperature and Relative Humidity Sensor** card. The system will automatically return to the main page.

<img src="https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%202.gif?raw=true" width="1000" />


**3. Add sensor command blocks:**
- Click on the **[ Multi ] - Temperature and Relative Humidity Sensor** category. You will see two available blocks:

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%203.gif?raw=true){{{width="1000" height="auto"}}}

**4. Write a simple program to display sensor data:**
- Use the **“show number”** block from the **Built-in Display** category to display the value on the GoGo Board screen.
- Insert the **"Temperature of SHT30 (°C)"** block into the show number block
- To display the value continuously, place everything inside the **“forever do each time wait…”** block from the **Loops** category. You can also set how often the value should be updated (e.g., every 1 second).

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%206.png?raw=true){{{width="500" height="auto"}}}

**5. Download and test your code:**
- Click **Download**, then click **Run Code** to start running your program.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Temp%20&%20RH/Temp%20&%20RH%207.gif?raw=true){{{width="1000" height="auto"}}}


::: details Additional information
  **Cautions**
- Avoid modifying wires or connecting them incorrectly, as this may damage the device.
- Do not touch the sensor head while it is operating, as it may affect detection accuracy.
- If the sensor does not work, check the voltage and wiring connections.
:::
