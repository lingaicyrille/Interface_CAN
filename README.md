# CAN(Controller Area Network)
CAN interface  
In this project, we will be exploring basic configuration, messages and filters. We will need a PIC18F66K80 PIM and a CAN/LIN interface board.  Carefully plug both into the PIC board.  The CAN/LIN board is already jumpered correctly so don’t change any jumpers.  The PIC board should be set for 5V.We will make a project with CANMain.c (and the LCD code.)  Connect to another group and test the firmware.  Either use a serial cable or connect jumpers from pin 2 to pin 2 and pin 7 to pin 7 of the DB9 connector. Then, we Change the CAN baud rate to 100 kbs.We Change the data payload of one of our messages to a value of our choice. We then add a new message ID and send it out on every 10th button press (instead of the message that would normally be sent out.) We set the payload to a value of our choice.and add an active filter so that only one of the messages is accepted.  The other messages should be filtered out.We set the filters to receive two of the three messages being sent by the other message received.  Filter out the other message.
 

Requires:  
* Explorer 18 Board
* Pickit 3
* PIC18F66K80 Plugin module (PIM)
* CAN/LIN PicTail board  
* DB9 - DB9 cable
* C Programming Language
