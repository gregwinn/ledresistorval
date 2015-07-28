# ledresistorval
Using this TI BASIC program on a TI-Nspire, it will calculate the current limiting resistor value needed for an LED

## Install

* Open the TI-Nspire CX CAS Student Software
* Plug your TI-Nspire into the computer
* Transfer the file "ledResistorProg.tns" to your TI-Nspire


## Run
##### 1) Push ```var``` and select ```ledresistorval```
```
 ledresistorval()
```

##### 2) Push ```enter``` and answer the questions.
* VCC -> The input voltage going to the LED.
* Forward Voltage -> The voltage the LED allows through.
* Forward Current -> Current needed to make the LED light up!

##### 3) Results
```
Input Value: 12
LED Voltage: 6.1
LED Current: .240
Resistor Value: 24.5833
```

Based on this example, using 12 volts with a forward voltage of 6.1 and forward current of .240mA you would need a 25 Ohms resistor.
