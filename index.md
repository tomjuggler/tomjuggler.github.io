Welcome to tomjuggler's software showcase

I am a circus performer who uses electronics and programming to enhance my performance. 


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

[Arduino EEProm](https://github.com/tomjuggler/EepromOnOffLedExample)

Here I show how to use the EEProm with Arduino to save states between boots. 
This method usually finds it's way into my projects in one form or another. 

[Generating Arduino code from Processing](https://github.com/tomjuggler/ArduinoCodeGeneratorBlinkExample)

The concept here is simple: get a Processing sketch to write your Arduino code for you. 
Here I provide a simple example to get the blink sketch generated, with a variable that the user can change. 
