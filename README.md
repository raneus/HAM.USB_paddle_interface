# HAM.USB_paddle_interface
The USB paddle interface based on STM32 microcontroller allows sending with an CW paddle instead of the computer keyboard.

STM32F401CCU6 core emulates keyboard buttons LeftControl for "dit" by and RightControl for "dah".
Paddle is connected to PB8:dit and PB9:dah, common pin of paddle is connected to GND.
