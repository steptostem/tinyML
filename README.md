# Introduction
<img src="https://einsteinpros.com/wp-content/uploads/2017/11/leaking-faucet-guide-solutions.jpg" height=20% width=20%>
This project aims to solve problem of using tinyML on low power deices.

## Background story
This project was inspiration from my past experience on using arduino devices but without ML.

## My Solution
I devised a way to use ML on arduino to make better projects

# Let's build it
## Hardware setup
Step 1: Connect Arduino board or fix arduino board to laptop and configure Edge Impulse SDK

<img src="https://github.com/steptostem/tinyML/blob/main/Images/20210617_225854_0000.png" height=30% width=30%>

Step 2: Software setup
We have used edge impulse which uses Tensorflow Lite Micro to perfrom ML on arduino.

```C++
if (true)
{
 digitalWrite(led, HIGH);
}
```
