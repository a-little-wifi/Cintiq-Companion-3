# Cintiq Companion 3

I have a dead Cintiq 13HD (pen+touch) that won't display anything. I know the lcd works, tested it in my Cintiq Companion, so the board must be dead. I wanna make a new one, that you can build a computer into, or with USB-C maybe. 

Wacom made a tablet PC based on the 13HD called the Cintiq Companion, then they made a Cintiq Companion 2, so this will be the Cintiq Companion 3.

Contains a USB2514Bi 4-port USB hub connected as follows:

- Port 1: Pen digitizer?
- Port 2: External USB port
- Port 3: USB UART converter
- Port 4: Touch panel digitizer

I thought the USB UART chip (SILABS CP2102) was for the pen digitizer, but it appears to connect to the RTD2483AD display controller chip instead, no idea what its function is.