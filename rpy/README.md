# Rpy - *Raspberry Pi Python*
**Rpy** 1.0 command line for the follow peripherics:

- ServoMotor 

# Rpy Usage
## ServoMotor:


sm, servo-move	:*Move the motor to specified grade from 0 to 180.*

Ex:<wtf>
rpy.py gpio=&lt;pin&gt; servo-move=&lt;grades 0-180&gt;

## Generics options:
p,  gpio		:*gpio motor pin.*


**NOTE:** 
	- The first argument of specified peripherics would be the 
	principal type (servo motor, camera, some sensor, etc ...) 
	
# For Developers