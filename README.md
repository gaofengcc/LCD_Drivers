# LCD_Drivers

ILI9488 (320x480) LCD + XPT2046 touch driver. Layered design for ESP32, STM32, Linux, etc.

## ESP-IDF

Add as component dir or git submodule at `source/drivers/LCD35`:

```cmake
list(APPEND EXTRA_COMPONENT_DIRS "source/drivers/LCD35")
```

App component: `REQUIRES LCD35`.

## Config

Edit `include/lcd_config.h` and `include/touch_config.h`.
