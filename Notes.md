# Library of Commands

- void setup()                   initalize and run only once
- void loop()                    main method; repeating code for the Arduino

- Serial.begin(9600)             this is how we connect string input to the Serial Monitor
- Serial.println();              prints out value. 

- pinMode(pin, mode)             pin is the pin number we want to configure, Mode is the behavior the pin uses
- digitalWrite(pin, value)       value can be LOW (no power) or HIGH (power)
- digitalRead(pin)               returns either LOW or HIGH, depending on what the pin is receiving
- analogRead(pin)                Returns an integer value representing the voltage on the given analog pin.
                                 0 means no voltage, 1023 means maximum voltage (likely 5V for RedBoard)
