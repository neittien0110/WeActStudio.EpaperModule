# WeAct Studio Epaper Module

## Tested Esp32-C3 DevKitM-1

- Hardware Specification

```plain
- VCC=3.3V
- Dependencies: GxPD2 of Jean-Marc Zingg, ver 1.5.2
- Board: Esp32-C3 DevKitM-1 Dual Usb
- EPD: WeAct 2.9" Black/White
```

- Sample code: (just comment the variable of 213" and uncomment the one of 290_BS. Compiling immediately) <https://github.com/WeActStudio/WeActStudio.EpaperModule>

must define board and type of ePD

```C
#define ESP32_C3_DUALUSB
//#define COLORED   
```

- Wires:

  !["5 threads"](./Images/20231004_231317.jpg)
  !["3 threads"](./Images/20231004_231406.jpg)
- [![youtube](https://i.ytimg.com/vi/yVmRT403PUM/maxresdefault.jpg)](https://youtu.be/yVmRT403PUM)

## Tested Esp32-C3 Super Mini

- Sample code: must uncomment

```C
#define ESP32_C3_SUPERMINI
#define COLORED
```

and comment other boards

- Wires:

  !["ESP32-C3 Super Mini](./Images/20231009_213106.jpg)
  !["result"](./Images/20231010_145658.jpg)
  !["result"](./Images/20231010_145658.jpg)
  !["result"](./Images/20231010_145712.jpg)
  !["6 threads"](./Images/20231010_145735.jpg)
  !["2 threads"](./Images/20231010_145741.jpg)
  ![view from top](./Images/20231010_145753.jpg)
  VCC=3.3V
- Dependencies: GxPD2 of Jean-Marc Zingg, ver 1.5.2
- Board: [Esp32-C3 Super Mini](https://vi.aliexpress.com/i/1005005319963906.html?gatewayAdapt=glo2vnm)
- EPD: WeAct 2.9" Black/White
- [![youtube](https://i.ytimg.com/vi/yVmRT403PUM/maxresdefault.jpg)](https://youtu.be/yVmRT403PUM)

## Some functions

1. setRotation(angle)

```C
  display.setRotation(0); //0=0* | 1=90* | 2 = 180 * | 3 = 270*
```

  !["display.setRotation(0)"](./Images/20231017_182837.jpg)

## EPD Board

!["Epaper Module"](./Images/1.png )
!["Epaper Module"](./Images/2.png )
