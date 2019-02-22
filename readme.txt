Simulation of airport using queue:

CASE

Aim is simulating a small and busy airport which has only one runway. 
In each unit of time, one plane can land or one plane can take off, but not both. 
That’s reason we need to simulate for plane which plane is ready to landing or ready to take-off.

Approach

In each unit of time, one plane can land or one plane can take off, but not
both. Planes arrive ready to land or to take off at random times, so at any
given moment of time, the runway may be idle or a plane may be landing
or taking off, and there may be several planes waiting either to land or
take off.

Queues

1st queue for arrivals plane (To land).
2nd queue for departure plane (To Take off).

PROBLEM CONSTRAINTS

1. The same runway is used for both landings and take-offs.
2. One plane can land or take off in a unit of time, but not both.
3. A random number of planes arrive in each time unit.
4. A plane waiting to land goes before one waiting to take off.
5. The planes that are waiting are kept in queues landing and takeoff, both of which have a strictly limited size.

SAMPLE INPUT:
Example: user give input like,
1. Up to what number of planes can be waiting to land or
take off at any time? 5
2. How many units of time will the simulation run? 1000
3. Expected number of arrivals per unit time? .48
4. Expected number of departures per unit time? .48