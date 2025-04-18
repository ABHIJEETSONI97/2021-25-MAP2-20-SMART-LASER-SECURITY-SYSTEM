# laser-security-alarm-
Laser based Security System is a type of security and alarm system that uses laser light and a light sensor. A security system protects our homes, offices, banks, lockers etc. from intrusion and unauthorised access. It makes some sound or noise when it detects any irregular activity.

### Working:

   This system for security uses the combination of LASER light and LDR. The LDR module has an onboard potentiometer to adjust the sensitivity of LDR, so that it only senses laser light falling onto it. The concept is quite simple and similar to what we see in movies where antique, priceless ornaments are protected under laser lights. As someone crosses these lights, an alarm runs on to indicate unauthorised presence. This project works similarly. In normal conditions, where there is always laser light falling on the LDR, the LDR module always gives a high signal to microcontroller. When someone crosses this laser light, it will behave as an obstruction between the LDR module and laser light, resulting in no light falling on LDR. In such cases LDR module gives a low signal to the microcontroller, which indicates it to switch on an alarm

### Tools & Technology:
* Programming language:C++
* Device: Arduino UNO 328p
* Other tools:  LDR, Laser, Buzzer


### Components Required:

* Arduino UNO 
* Breadboard
* LDR(Light Dependent Resistance)
* Laser
* Buzzer
* Jumper wires
* Lcd display
* I2c module
* Switch
* 
#Step-by-Step Instructions

1. Clone or Download the Repo

Open the GitHub repo: https://github.com/bbx10/Blink

Click "Code" > "Download ZIP", then extract it
OR
Use Git:

git clone https://github.com/bbx10/Blink.git


2. Open the Code in Arduino IDE

Open Arduino IDE

Go to File > Open

Navigate to the Blink folder and open the file Blink.ino


3. Connect Your Arduino

Plug in your Arduino via USB

Go to Tools > Board and select your board (e.g., Arduino Uno)

Go to Tools > Port and select the correct COM port


4. Upload the Code

Click the Upload button (the right arrow icon)

Wait for the "Done uploading" message


5. Watch the LED Blink

The onboard LED (usually pin 13) should blink every second
