# Shut_up_Button
I will show you, how a arduino can write things.

You need a 3d-printer, arduino Leonardo and buttons
I used PLA with 200C Celsius Nozzel and 50C Celsius hot bed.
After printing i soldered the buttons together
# Prints
![Boxbild2](https://user-images.githubusercontent.com/72698237/128365354-cc92fe91-20ee-456f-917a-1871b2276c3e.PNG ) 
![Boxbild3](https://user-images.githubusercontent.com/72698237/128365360-a2d61cc6-b7ec-4d5f-9afd-4b68fab1fff3.PNG)
![Boxbild1](https://user-images.githubusercontent.com/72698237/128365364-94bcb2fa-a07c-4d8f-b751-46f4605c3285.PNG)

# How to connect

![Schaltbild](https://user-images.githubusercontent.com/72698237/128364143-526c955b-c6db-4f8c-8b34-a1935d15796f.PNG)


# Example code
    #include <Keyboard.h>

    void setup() {
     // make pin 2 an input and turn on the
     // pullup resistor so it goes high unless
     // connected to ground:
      pinMode(7, INPUT_PULLUP);
     Keyboard.begin();
     }

    void loop() {
     //if the button is pressed
     if (digitalRead(7) == LOW) {
       //Send the message
       Keyboard.println("NOOB");    
       delay(50);
     }
    }


_More Information:_
https://www.arduino.cc/reference/en/language/functions/usb/keyboard/


# Subscribe to my YouTube Channel for more Projects

_https://www.youtube.com/channel/UCUKGpRmZLFh_AmThMi59b7w_









Button: (https://www.amazon.de/WINOMO-Premium-Mikroschalter-Roller-Endschalter/dp/B01LWI1PKU/ref=sr_1_53?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=schalter+l%C3%B6ten&qid=1628159677&sr=8-53)

