常见问题
================

1.AT 指令默认波特率多少？
-----------------------

默认波特率是 115200 bps，使用 UART0 进行通信

2.模组发送AT指令无响应？
----------------------

- 复位模组，检查串口是否有信息输出，若无信息，请检查电源以及接线是否正确。
- 检查是否进入了透传模式，可尝试发送+++退出(不要加回车换行符)；

3.AT固件支持哪些配网？
-------------------

- 通过MCU写passwd ssid
- 通过开启AP热点方式，AP配网
- 智能配网，支持airkiss和smartconfig

4.烧录问题总结
------------

`**W600固件烧录指南** <upload/application_note/download_firmware>`__
