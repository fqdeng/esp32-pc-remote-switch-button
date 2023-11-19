Esp32 PC remote switch button
====================


## compile:
```c
/**
 *
 * #define EXAMPLE_ESP_WIFI_SSID      ""
 * #define EXAMPLE_ESP_WIFI_PASS      ""
 */
#include "wifi_password.h" // put the comment to this file

```
change it , use esp32 sdk to build it


## usage:
```bash 
curl -X POST http://{your esp32 wifi connect ip}/click
```
