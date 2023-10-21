# 555ic_motordriver
Motor speed controller using 555 timer ic in astable multivibrator mode to produce the PWM pulses necessary for control over the speed of the motor.
A 555 timer ic, operating in astable multivibrator mode produces a PWM (pulse with modulated) output from the discharge pin (7th pin on the ic). The on-time and off-time of the pulse or the duration of the pules depend on the ratio of resistors and capacitors used. Time on(ton) = 0.693(R1 + R2)C and time off (toff) = 0.693*R2*C. 

The duty cycle is the time for which the signal is active (ton/total time). Ttotal = ton + toff = (R1 + R2)/(R1 + 2*R2)%.

A motor needs a lot of current to rotate, which cannot be produced by a 555 ic pin. So we can use a MOSFET or a BJT to act as a power circuit.

N-MOSFET is a voltage-controlled device, when voltage is given to the base it turns on i.e. connects the drain and source completing the circuit. The on-and-off pulses turn the MOSFET on and off several times a second (duty cycle times a second). The voltage to the motor gets pulsated and thus the speed can be controlled. 

This is one of the applications of a 555 timer ic, which is widely used as an LED control circuit. The ic might have a limited use case but the concept of PWM can be used to the wildest of our imaginations. 

The following are the circuit diagram, breadboard connections, and circuit simulation of the project.A 555 timer ic, operating in astable multivibrator mode produces a PWM (pulse with modulated) output from the discharge pin (7th pin on the ic). The on-time and off-time of the pulse or the duration of the pules depend on the ratio of resistors and capacitors used. Time on(ton) = 0.693(R1 + R2)C and time off (toff) = 0.693*R2*C. The duty cycle is the time for which the signal is active (ton/total time). Ttotal = ton + toff = (R1 + R2)/(R1 + 2*R2)%. A motor needs a lot of current to rotate, which cannot be produced by a 555 ic pin. So we can use a MOSFET or a BJT to act as a power circuit. N-MOSFET is a voltage-controlled device, when voltage is given to the base it turns on i.e. connects the drain and source completing the circuit. The on-and-off pulses turn the MOSFET on and off several times a second (duty cycle times a second). The voltage to the motor gets pulsated and thus the speed can be controlled. This is one of the applications of a 555 timer ic, which is widely used as an LED control circuit. The ic might have a limited use case but the concept of PWM can be used to the wildest of our imaginations. The following are the circuit diagram, breadboard connections, and circuit simulation of the project.

