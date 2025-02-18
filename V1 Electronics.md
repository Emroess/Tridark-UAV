## V1 Electronics:
In order to fly Tridark and have it not just be a fancy paper weight, some electrical equipment are necessary:

### Motors 
Motors are a requirement to produce lift and thrust. But what kind of motors should I choose? The largest factor I am looking at is KV or the revolutions per minute per one applied volt (rpm per volt) with no load on the motor. For example, a 1000 KV motor would spin at 1200 rpm if supplied with 12 volts under no load. 

    KV= RPM/V
So then it is true that the higher the KV the faster the motor will spin with the inverse being true as well. But since we live in a world constrained by friction, aerodynamic drag, and heat, speed is limited by torque. For example, a higher KV motor will reach its maximum speed more quickly but have a lower powered top speed. Lower KV motors produce higher torque for a given power input, at the expense of lower speed.

What does this mean for Tridark? 

Flightory, the company that designs the airframe Tridark is based on, recommends a 1300KV-1500KV motor depending on the payload weight desired. I know that a lower KV motor would be able to power a larger diameter propeller and produce more thrust. I have plans to add heavier electrical equipment and sensors to the airframe in the future, so a lower KV makes sense. Future tests will need to be done to measure power consumption over the desired speed/load range. Propeller pitch and diameter also determine the amount of power consumed and the amount of Power **(P = T * ω)** produced. Future testing will need to be done in order to find a balance between thrust and consumed power. For initial testing, three 1300KV motors will be purchased and installed in a tricopter configuration.

![Image of Tricopter Configuration](https://ardupilot.org/copter/_images/APM_2_5_MOTORS_TRI.jpg)
