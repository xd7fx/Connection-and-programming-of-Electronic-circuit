# Arduino Servo Control

## Description
This project uses an Arduino Uno to control 8 servo motors. Connect the servos to digital pins 2-9. The code moves the first 6 servos to 180 degrees, the last 2 to 90 degrees, then all to 0 degrees, with a 1500ms delay between movements. Connect the servos to the breadboard, upload the code, and the servos will move as specified.

## Hardware Setup:
1. Connect each of the 8 servo motors to the breadboard and ensure each servo's signal wire is connected to the appropriate pin on the Arduino as shown in the image.
2. The power and ground wires of each servo should be connected to the 5V and GND rails of the breadboard respectively.
3. Ensure the Arduino is connected to your computer via USB for both power and data transfer.

## Software Setup:
1. Open the Arduino IDE on your computer.
2. Copy and paste the provided code into the Arduino IDE.
3. Connect the Arduino to your computer.
4. Select the appropriate board and port from the 'Tools' menu in the Arduino IDE.
5. Upload the code to the Arduino by clicking the upload button (right arrow icon).

## Running the Project:
1. Once the code is uploaded, the Arduino will start controlling the servo motors according to the logic defined in the loop function.
2. The servos will move to 180 degrees and 90 degrees, then return to 0 degrees after a delay of 1500 milliseconds.
3. This setup and code will allow you to control 8 servos connected to an Arduino Uno. Ensure all connections are secure to avoid any issues during operation.
