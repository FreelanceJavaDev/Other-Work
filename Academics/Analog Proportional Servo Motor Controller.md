# This concerns a paper I wrote on an Analog Proportional Servo Motor Controller I had built tested and then improved
The servo motor controller consisted of transistors resistors a gear motor and a mechanically fixed potentiometer to the output shaft of the gear motor.  Then an input is provided by a second potentiometer.

## Interesting findings
A normal 9 volt battery didn't have the energy capacity to run either verison and the output drops like a brick, however 6 AA batteries work for both versions, making what I like to call a super 9 volt battery.  Now in testing the deadband of a the servo motor I got a sizeable deadband.  In the improved version I noticed a gear motor kit on clearance.  It looked dangerous, had serious torque power, but took 200 mA and 12V as compared to the one I had before with 2A and 5V. The switch of the servo motors allowed me to reduce the circuit complexity.  In attempting to find the dead band to find a testing point for the improved version, well I couldn't find it.  The setup became so sensitive that changing the pressure on a wire invoked a movement.  There isn't much resistance in a 24 AWG wire. The potentiometers were 10k\Omega &PlusMinus20% and the resistors were various fixed 0.25 Watt &PlusMinus5% resistors.  

This was by no means a narrow tolerance setup.  Since I couldn't find the deadband, I presumed it existed, but my testing methodology wasn't precise enough to find it.  It could have easily been hidden by the tolerance variation and heat dissipation.

