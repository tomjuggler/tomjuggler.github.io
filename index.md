Welcome to tomjuggler's software showcase

I am a circus performer and developer who uses electronics and programming to enhance my performance. I document some of my projects at [circussscientist.com](https://circusscientist.com)

CV: [circussscientist.com/cv](https://circusscientist.com/cv)

Portfolio site: [portfolio.devsoft.co.za](https://portfolio.devsoft.co.za)

```java
import play.*
import work.*

boolean isLinux = true;
boolean isArduino = true;

void setup(){
  if(isLinux || isArduino){
   play(); 
  } else{
   work();
  }
}
```

Some of my favorite past projects: 

[LED Website Indicator](https://ledindicator.devsoft.co.za):

An LED flashes when anyone visits one of your websites. Sign up for free and use the D1 mini to check one site or buy the full RGB version for up to 7 sites. WordPress plug-in, and Python library available for easy integration with your own site back-end. 

[Monkey Detector Android App](https://github.com/tomjuggler/Monkey-Detector):

Machine learning Android App to detect the presence of Vervet Monkeys (written in Kotlin). Check out the full tutorial at: [https://www.circusscientist.com/monkey-detecting-sprinkler-overview/](https://www.circusscientist.com/monkey-detecting-sprinkler-overview/)

I made an app for Android based on the above project, called Pet Detector. You can find it on the [Play Store](https://play.google.com/store/apps/details?id=za.co.tombigtop.petdetector_free_version)

[parseCoronaVirusSA](https://github.com/tomjuggler/parseCoronavirusSA):

Parsing a reliable source of virus information for my country into a map, using Processing. Full tutorial with a graph and more on the website: [https://www.circusscientist.com/parsing-online-corona-virus-data-into-a-map-with-processing/](https://www.circusscientist.com/parsing-online-corona-virus-data-into-a-map-with-processing/)

[SmartPoi Android App](https://github.com/tomjuggler/SmartPoi-Android-App) and [SmartPoi ESP8266 Firmware](https://github.com/tomjuggler/SmartPoi-Firmware):

My 6 year long project to create the worlds first WiFi Streaming Graphic Poi. Used in many shows, I even sold a pair. This is the project where I learned the most. A bit of a mess but it works! Check out the write up here: [https://www.circusscientist.com/smart-poi-overview/](https://www.circusscientist.com/smart-poi-overview/)

This project is busy being updated to a web based version, with PlatformIO based firmware for the ESP32, called "Magic Poi". The new version currently lives here: [http://magicpoi.circusscientist.com](http://magicpoi.circusscientist.com) although at some point it will move over to [http://magicpoi.com](http://magicpoi.com)


[Arduino EEProm](https://github.com/tomjuggler/EepromOnOffLedExample):

Here I show how to use the EEProm with Arduino to save states between boots. 
This method usually finds it's way into my projects in one form or another. 

[Generating Arduino code from Processing](https://github.com/tomjuggler/ArduinoCodeGeneratorBlinkExample):

The concept here is simple: get a Processing sketch to write your Arduino code for you. 
Here I provide a simple example to get the blink sketch generated, with a variable that the user can change. 
