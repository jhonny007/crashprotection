# crashprotection
Platform to track your direction and warn you about all traffic that comes in your way.

## description
About 3500 people were killed by accident in street traffic in the year 2016 in Germany. 100 thousands were injured and the initiators
are inflected by their guilt. The financial costs are gigantic and have to be paid by the insurances and that meens all of us.

## Is it possible to cut down the number of accidents significally?
I think yes - with a crash protection system that warns you.

## What should the system do?
It should track the speed and direction of all the traffic participiants. If a crash is likly to occur a warning could probably move
the attention to the dangerous situation. For example a car driver gets informed about a bicycle driver approaching from the right.

## How does it work?
With the help of GPS the position, direction and speed of an participiant is calculated and sent to the central server. The answer contains
all data about participiants that are in a relevant distance. The client calculates if there are crashes likely and generates a warning.

## What is important?
It is indispensable that there exists only one system and to add all traffic participiants (or at least as many as possible). If you like
to develop a similar system please contact me and we develop it together. Otherwise our effort is useless because the system can only work efficiently when the information about the reality is complete.

### Use cases

## Use case 1:
The client sends my means of transport, current position, direction and speed to the server.

## Use case 2:
The servers sends me means of transport, current position, direction and speed of others.

## Data

### Means Of Transport
'''
pedestrian
bicycle
motorbike
car
'''



