Component list:  LED
Added some

Resistor 

Power source 

Multimeter

Diode

Breadboard

Arduino 

Push button

HandsOn:

First we made 3 circuits, simple-, serie- and parallel. We controlled the current with a resistor so that the LED wouldn't burn. After that we learned how to work with a multimeter. Then we used a breadboard and measured the resistance after adding resistors in serie and in parallel. Below you can see a screenshot of the components. 

![](https://lh6.googleusercontent.com/IYMGGRL4byLVwtVbma2rmcrx42uAq9yNV68syFz2Dqt28C0hMsPfBFtAZEuyq2o2eX2NLssyfUzMWRQOEzC4qR_SANe7Xw5IeWf9JMGUVkcAqVGaWdbKGU4B8wQMMAFphAkIbVTRJn9p2cTNYK4nKQ)

After that we used an arduino to make a LED blink by the instructions that are written in a code. In a screenshot below, you can see how it is built.

![](https://lh6.googleusercontent.com/ATr2WajNhTnLsUO0bHgjOYrqkd70pneFSd_oDPq58Aw6taGFJhii_7gYE2bIYSJjP8tQ1fUx6Oui0jZM895BhUMZx2Fycsf8iLJ46OrQWe4wjETXSZqxl4QUbPUWmF9o9KkR2K0rtgMCk3f3c3DPIg)

Code:

In this code we are going to make the LED blink one second. If we are going to push the button it won't blink anymore. It will stay on.

int led = 2;

int button = 3;

void setup (){

  pinMode(led, OUTPUT);

  pinMode (button, INPUT);

}

void loop (){

  if (digitalRead(button) == LOW) {

  digitalWrite(led, HIGH);// other option: (2,1)

  delay(500);// in milliseconds

  digitalWrite(led, LOW);

  delay(500);

  } else 

  digitalWrite(led, HIGH);// other option: (2,1)

}

Mistakes:

My first mistake was that I didn't put the wire on the right place in the breadboard sometimes. My second mistake was that I didn't hold the push button in, and I thought that my code was wrong. Some other mistakes were that I would make little writing mistakes in the code and I would get an error.

Day 2 (6 sept):
===============

objective :  Usage of analog input.

Introduction to a potentiometer.

Coding a LED with a potentiometer and temperature sensor.

Component list:  LED

Potentiometer

Temperature sensor

Breadboard

Arduino 

HandsOn:

First we made a circuit with a potentiometer in it and we wrote a code to read the value of the potentiometer.

![](https://lh4.googleusercontent.com/PsQ7Kmn-TaLdhW7n9zK0a-Z9Ov0sM_ZUuz38lhc08vc5dK_SsThyOPYSf0VhqimZTh53bE-TTyD8pPX7KHDb-QkQWHkyaGiztBdnqm_FByHxV5HMov-t-Nx7X1wqcbNjvV7vOt0vhaJX2LjV1mDDryU)