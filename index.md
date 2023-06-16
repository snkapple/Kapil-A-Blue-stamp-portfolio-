# Mini Tank Robot 

I decided to build a mini-tank robot. It can use treads to move, and it also has various sensors that it can use to detect its environment and have various reactions. 

| **Engineer** | **School**                 | **Area of Interest**   | **Grade** |
|:--:|:--:|:--:|:--:|
| Kapil A       | Menlo Atherton High school | Electrical Engineering | Incoming Sophomore 



<img src="Kapil-Headshot.png" width="400" height="500">
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
I am building a mini tank robot. Right now I have just built it so there is no code or anything to run it.
- Building the tank involved a few things I first had to assemble the wheel and the drive of it. For that, there was a prebuilt structure to which I could mount a DC motor to which I attached a wheel, I would also have another wheel on the same piece which would be connected so they can turn each other. There are two of those drives and I would mount a panel on top of those which contains the electronics such as the Arduino microcontroller and the attachments like the motor controller and the sensor shield.
- I have been able to test various different parts of the electronics and get them working successfully such as the ultrasonic sensor, the photoresistors, the servo, and the Bluetooth module. These sensors can be used for different things if I want my robot to react to its environment, for example, if I want the robot to not hit an object I would use the Ultrasonic sensor, and if I wanted it to react to its light level I would use the photoresistor.   One challenge I faced was with the software particularly when it came to the IR sensor which I wasn't able to get working properly because the library wasn't working.
- After this, I plan to get the IR sensor working and get remote-controlled driving capabilities with either the Bluetooth or IR sensor and use those inputs to power the motors.  
# Starter Project
My starter project was the custom Arduino project.
- I made an Arduino that when you are at least ten centimeters from the ultrasonic sensor you would turn on an LED.
- I used an Arduino for programming and controlling the sensor, an adafruit proto shield to solder onto and to contain my circuit, an led to provide an output, a resistor to make sure my led wouldn't burn out from too much power, various wires, and an ultrasonic sensor to provide an input. 
- A challenge I faced was getting the circuit right and issues with shorting.
  I first designed the circuit on a breadboard which taught me a lot about how circuits work and Power Rails, but when soldering it the circuit kept shorting. I realized that the board to which I was soldering the components had power rails that were already powered by a 5-volt connection so when I connected them to ground it would short. What I had to do was remake the circuit on a different part of the board which wouldn't already have a five-volt connection. For that, I had to make my own connections between the components because they didn't have power rails. 


<iframe width="560" height="315" src="https://www.youtube.com/embed/oUL4bk-k7ME" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
