## Electronics and Concepts
In order to fly Tridark some electrical equipment and undersanding of how they work is necessary:

## What is Dshot and why am I using it?
**Well because it’s cool…** and none of the old rc guys that fly hobby planes seem to be using it.

Dshot is a cooler, faster, and digital younger brother to the traditional analog PWM (Pulse Width Modulation) control signal. To understand what Dshot is, let's first dive into our understanding of what PWM is and how it can be used to control throttle level in a multirotor drone. Pulse width modulation is simply any form of controlling an analog rectangular wave by varying its duty cycle or pulse width.

![Image of PWM SIGNAL](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.ndA6xHeXSARmSkA4Ehre6wHaEK%26pid%3DApi&f=1&ipt=0b117cb7e7499f6faf677980027a5bc864fd6b8e47c9a8bed53d966e66f95f2e&ipo=images)

When an electronic speed controller(ESC) receives a PWM signal, it measures the pulse widths and then outputs the corresponding programmed motor output. It is a simple and robust system that has been in use since 1849. So if it’s so simple and robust (simplicity is the key in good engineering) why the heck am I not using it?? 



Well…I can but I decided that was too easy. There are also some flaws with PWM, so let me explain. 

Because PWM is analog it is susceptible to unwanted timing variations in the pulse width. This can happen when there are sufficient amounts of electromagnetic interference between the transmitting and receiving electrical components. On multirotor drones, a great source of this are motors or current induced in the wiring powering the motors.

(WORK IN PROGRESS 5/6/25)

## Choosing Motors 
Motors are a requirement to produce lift and thrust. But what kind of motors should I choose? The largest factor I am looking at is KV or the revolutions per minute per one applied volt (rpm per volt) with no load on the motor. For example, a 1000 KV motor would spin at 1200 rpm if supplied with 12 volts under no load. 

    KV= RPM/V
So then it is true that the higher the KV the faster the motor will spin with the inverse being true as well. But since we live in a world constrained by friction, aerodynamic drag, and heat, speed is limited by torque. For example, a higher KV motor will reach its maximum speed more quickly but have a lower powered top speed. Lower KV motors produce higher torque for a given power input, at the expense of lower speed.

What does this mean for Tridark? 

Flightory, the company that designs the airframe Tridark is based on, recommends a 1300KV-1500KV motor depending on the payload weight desired. I know that a lower KV motor would be able to power a larger diameter propeller and produce more thrust. I have plans to add heavier electrical equipment and sensors to the airframe in the future, so a lower KV makes sense. Future tests will need to be done to measure power consumption over the desired speed/load range. Propeller pitch and diameter also determine the amount of power consumed and the amount of Power **(P = T * ω)** produced. Future testing will need to be done in order to find a balance between thrust and consumed power. For initial testing, three 1300KV motors will be purchased and installed in a tricopter configuration.

![Image of Tricopter Configuration](https://ardupilot.org/copter/_images/APM_2_5_MOTORS_TRI.jpg)
