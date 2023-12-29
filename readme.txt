This LVGL demo project is created by Gábor Kiss-Vámosi
(https://github.com/lvgl/lv_port_stm32f746_disco) and ported to Embeetle IDE by Aleksei
Prokopov (https://github.com/roboter and
https://github.com/roboter/Hardware/tree/main/STM32/32F746GDISCOVERY/embeetle/lv_port_stm32f746_disco)

Note:
It's important to add the -DSTM32F7 flag to the TARGET_CFLAGS and
TARGET_CXXFLAGS in '<project>/config/dashboard.mk' such that LVGL
works properly.