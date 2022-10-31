# HX3600-Arduino-Library
Arduino Library for the HX3603 Heartrate sensor for the nRF52 Bluetooth Micro

This sensor is used in the "second-generation" Da Fit watches, based on the nRF52840.
I have a Kospet ROCK to test on.








### You can support ATC's work via paypal: https://paypal.me/hoverboard1 this keeps projects like this comming.

It includes a closed source .a file, to get the Arduino IDE recognize it you need to edit the Platform.txt from the nRF52 library.


Add: ```compiler.libraries.ldflags=``` somewhere as a new line.

also add: ```{compiler.libraries.ldflags}``` somewhere ad the end of line ```combine.pattern```

For more infos watch this video for another Heartrate Sensor: 

[![YoutubeVideo](https://img.youtube.com/vi/E0W65KbaeA8/0.jpg)](https://www.youtube.com/watch?v=E0W65KbaeA8)

Demo video:

[![YoutubeVideo](https://img.youtube.com/vi/I8Ch9Db_a7M/0.jpg)](https://www.youtube.com/watch?v=I8Ch9Db_a7M)
