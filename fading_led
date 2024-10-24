int ledPin = 11; // the PWM pin the LED is attached to
int brightness = 0; // how bright the LED is 
int fadeAmount = 5; // how many points to fade the LED by
void setup() {
pinMode(ledPin, OUTPUT); // declare ledPin to be an output

}
void loop() {
analogWrite(ledPin, brightness); // set the brightness of ledPin
brightness = brightness + fadeAmount; // change the brightness for next time through the loop: 
if (brightness >= 255 || brightness <= 0) { // Hint: brightness should be in [0,255]
fadeAmount = -fadeAmount; // reverse the direction of the fading at the ends of the fade
}
delay(30); // wait for 30 milliseconds to see the dimming effect
}

