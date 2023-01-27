# Day_Face-Recognition_Door_lock

Developing IOS app using swift called day. The first feature in this application will be the Room safety tab. 
The room safety tab will be linked with bluetooth to the circuit diagram (1), containing a bluetooth ESP32 board and camera. 

This tab will exist such that the user can press a "lock" and "unlock" key to lock the room or unlock it. These features will be embedded into the ESP32, signaling it to unlock the solenoid lock in the circuit or unlock it.

An additional feature is when if a person tries to enter the room, the camera will cature the image of this person and compare it to a gathered dataset (pictures of the main user that was used to train the ESP32 and bluetooth camera to recognize the main user). If the person enterring the room does not match the main user. The image of the person will be sent to the main user in the application, labelled "INTRUDER ALERT!". If the user wishes to unlock the door they can, otherwise they can keep the door locked to keep the intruder out of the room.
