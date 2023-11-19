Esp32 PC remote switch button
====================


## Compile:
```c
/**
 *
 * #define EXAMPLE_ESP_WIFI_SSID      ""
 * #define EXAMPLE_ESP_WIFI_PASS      ""
 */
#include "wifi_password.h" // put the comment to this file

```
change it , use esp32 sdk to build it


## Usage:
```bash 
curl -X POST http://{your esp32 wifi connect ip}/click
```


## Show:

<img src="./image/main_board.jpg" width="50%">
<img src="./image/switch.jpg" width="50%">
