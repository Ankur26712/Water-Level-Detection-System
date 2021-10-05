Water-Level-Detection-System
The objective of this project is to notify user the amount of water present in the overhead water tank.
The transmitter circuit makes use of an ultrasonic sensor and Arduino board to measure the water level in terms of
distance. This data is sent to the receiver circuit using RF communication to calculate the distance at what level the
water is present and produce the output percentage accordingly and reflect in the screen.

This project helps in reduction in wastage of water, it can be implemented in very large scale i.e. as a part of river
flow management system or in small scale i.e. households.
All components are interfaced with the Arduino and works by automation as per uploaded. 0% is the condition of
the tank where the quantity of water present in it is null and finally 100% is maximum condition. We have to
monitor and maintain the tank when the water in it is pouring in it.

The existing system works with many number of wires let us take a tank which is divided into percentages like
10%,20%, . . . 100%. Every wire is of different size kept at different percentages of the tank [3]. If the water
present in the tank is 10% the water touches only one wire so LCD returns the amount of water present in it.
This take much time in implementation. As water touches the wires may get damaged.
The above figure shows the existing water level management system here in this system they hang the wires into
water and each wire is connected to an LED. here the water is touching all 7 wires so the wire 7 returns that water
in tank is maximum the LED connected to the wire 7 will glow up, likely when the water level is only touching
wire 1 similarly the connected LED will glow up and we will know the percentage of water present in the tank.
Proposed system:
This proposed system works under automation and contains the components like Arduino, ultrasonic sensor, motor
pump, relay, led, buzzer and LCD in which each component has its own functionality but Arduino looks like heart
of the project as all the components are interfaced with Arduino. The ultrasonic sensor plays major role in 
determining the water level present in the tank. This sensor is fitted under the lid of the tank and uses the concept
called “echo”. The sensor contains two small openings called trig and echo. The trig works like a small speaker in
which it sends the ultrasonic waves and the echo acts as a small microphone in which it receives the reflected
waves which are sent by trig and this echo returns the distance. So by this we are known of water level in the tank
through LCD. Another advantage of this proposed system is motor automation. We have designed a code that
whenever the tank is getting low about of 10% the motor automatically starts and stops when the tank reaches to
90% so here no one required for controlling to motor this is the main advantage of proposed system. Since no
component touches the water there is no chance of damage to the components whereas in the existing system
which contains wires that are placed in water can get damaged after sometime. 

FEASIBILITY STUDY
ACCESSIBILITY
Accessibility is a general term used to describe the degree to which a product, device, service,or
environment is accessible by as many people as possible .It is very cost effective and work for the welfare
of the nature.
 MAINTAINABILITY:
In software engineering, maintain ability is the ease with which a software product can be modified in
order to include new functionalities can be added in the project based on the user requirements just by
adding the appropriate files to existing project using programming languages. Since the programming is
very simple, it is easier to find and correct the defects and to make the changes in the project.
 SCALABILITY:
System is capable of handling increase total throughput under an increased load when resources (typically
hardware) are added. System can work normally under situations when the tank level is given if we want
to implement it the large scale area then we need high quality if sensors which provide accurate and good
data through which the calculation can be done.
 PORTABILITY:
Portability is one of the key concepts of high-level programming. Portability is the software code base
feature to be able to reuse the existing code instead of creating new code when moving software from an
environment to another. Project can be executed under different operation conditions provided it meet its
minimum configurations. Only system files and dependent assemblies would have to be configured in such
case.
VALIDATION:
It is the process of checking that a software system meets specifications and that it fulfils its intended purpose.
It may also be referred to as software quality control. It is normally the responsibility of software testers as part of
the software development lifecycle.
Software validation checks that the software product satisfies or fits the intended use (high-level checking) i.e. the
software meets the user requirements, not as specification arte facts or as needs of the who will operate the
software only; but as the needs of all the stakeholders.

Saves Power
By using our project, we can save power. I can be used in places where there is problem of Load Shedding.
As it is automatically controlled, it limits the amount of electricity. As today energy conservation is the
utmost need, using one of these devices is useful.
 Saves Money
Now, as we know that automatic water level controller conserves power, it saves money as well. Water
regulation is optimized using this device that means wastes electricity and wasted water is kept at a
minimum. This saves a huge amount of money along with manpower.
 Works Automatically
The utmost advantage of water level controller is that it can work on its own. It is because of relay and
timer switches that there is no need to operate them manually. This means that a lot of human work is
reduced.
 Maximizes Water
Additionally, water usage can be maximized with a water level controller. Often, water pumps get more
use during the middle of the day. A water level controller is helpful because it automatically provides
more water during the day.


CONCLUSION
Prototype of Water Level Detection System has been tested and reasonably good performance is shown based on
the test result. The main contribution of this performance is the ping sensor calibration by adjusting calculation of
distance based on an actual data. Testing need to be carried out for the real fluctuated water surface condition to get
the system performance in the real condition.
We have successfully run a test on different tanks and the water level of each tank is shown to us on the output
screen and when we remove the water it will also show the decrease in the percentage of the water level hence our
project runs on every possibility we can calculate the distance and percentage accurately in different climate such
as when the water is cold, hot, warm or moderate temperature.
The water level data is successfully displayed locally or remotely, therefore this prototype can be used as a part of
the bigger system, such as, river flow management system which controls the stream to minimize the flood.
The receiver can act as a water level data feeder that can be transmit the data remotely to the server.
Since computer is used as a part of receiver module, therefore more sophisticated system can be developed to
display and analysis time series water level data, instead of only displaying the current.
