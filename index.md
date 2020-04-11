Welcome to tomjuggler's software showcase

I am a circus performer who uses electronics and programming to enhance my performance. Lately I have been documenting my projects at [circussscientist.com](https://circusscientist.com)


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

Here I will showcase all my (open source) Circus Scientist related projects. 

Some of my favorite code examples: 

[Monkey Detector Android App](https://github.com/tomjuggler/Monkey-Detector)
Machine learning Android App to detect the presence of Vervet Monkeys (written in Kotlin). Check out the full tutorial at: [https://www.circusscientist.com/monkey-detecting-sprinkler-overview/](https://www.circusscientist.com/monkey-detecting-sprinkler-overview/)

[parseCoronaVirusSA](https://github.com/tomjuggler/parseCoronavirusSA)
Parsing a reliable source of virus information for my country into a map, using Processing. Full tutorial with a graph and more on the website: [https://www.circusscientist.com/parsing-online-corona-virus-data-into-a-map-with-processing/](https://www.circusscientist.com/parsing-online-corona-virus-data-into-a-map-with-processing/)

[SmartPoi Android App](https://github.com/tomjuggler/SmartPoi-Android-App) and [SmartPoi ESP8266 Firmware](https://github.com/tomjuggler/SmartPoi-Firmware) 
My 6 year long project to create the worlds first WiFi Streaming Graphic Poi. Used in many shows, I even sold a pair. This is the project where I learned the most. A bit of a mess but it works! Check out the write up here: [https://www.circusscientist.com/smart-poi-overview/](https://www.circusscientist.com/smart-poi-overview/)


[Arduino EEProm](https://github.com/tomjuggler/EepromOnOffLedExample)
Here I show how to use the EEProm with Arduino to save states between boots. 
This method usually finds it's way into my projects in one form or another. 

[Generating Arduino code from Processing](https://github.com/tomjuggler/ArduinoCodeGeneratorBlinkExample)
The concept here is simple: get a Processing sketch to write your Arduino code for you. 
Here I provide a simple example to get the blink sketch generated, with a variable that the user can change. 
