# Speed-Control-Of-Dc-Motor-Using-Pwm
Speed Control Of Dc Motor Using Pwm

##PROGRAM 
```
const int motorPin = 9;
const int potPin = A0;

void setup() {
pinMode (motorPin, OUTPUT) ;

}

void loop() {
int potValue = analogRead (potPin) ;
int pwmValue = map (potValue, 0, 1023, 0, 255);
analogWrite (motorPin, pwmValue);
}
```
##OUTPUT
<img width="1047" height="556" alt="image" src="https://github.com/user-attachments/assets/48eefd3e-6728-4394-8dea-b5662ec59181" />
<img width="1042" height="552" alt="image" src="https://github.com/user-attachments/assets/8a78c798-1dd8-4dde-97ba-2c95e4a4ba52" />


##RESULT

Thus, the Speed Control Of Dc Motor Using Pwm is verified

