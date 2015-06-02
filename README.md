# GlediatorOctoWs2811
An arduino sketch to run multiple strips of LEDS on a OctoWS2811 adapter via Glediator.


Based on the original code from mike5ch at https://github.com/mike5ch/teensy3GLEDIATOR ( i know i should fork or branch or something but  i am new to github)

I found that the original code could only manage a single LED Strip and thus this is the modification of Mike5ch's code to allow to run multiple strips. This has been tested with 2 x 60 led strips of WS2812b on a raspberry PI and Windows 8.1 x64 and no more. Please follow Mike5ch's details on how to configure the USB ports for your specific OS. Please note under windows we used the base USB driver not the one provided by Mike5ch

Modify the variables ledsperstrip and no strips according to your configuration.

I hope this helps someone down the line, i now have a very happy lighting guy after getting this working :-D

Enjoy
