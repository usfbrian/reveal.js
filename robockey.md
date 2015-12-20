Lessons Learned
===============

LOOK AT EVERY DETAIL
- Mechanical
- Electrical
- Software

MECHANICAL: LEAVE TOLERANCE
- Wheels rub against walls, particularly after impacts
- Buy/create extra everything

ELECTRICAL: LEAVE TOLERANCE
- Reconsider using an LM7805 to step down from 22 V
- Test motor current under loading using a power supply
- Motor driver should push enough current
- Fabricated PCBs should have extra holes for ground, each voltage source, and certain I/O

SOFTWARE: LEAVE TOLERANCE
- Only condense code if needed
  . number and type of pins used
  . use of certain headers e.g. math.h
- Incremental performance gains
  . non-float sind/cosd/atan2 (final memory use 51%)
  . min frequency needed for each process

SOFTWARE: ADVANCED
- Use communication to share relevant data e.g. puck location estimate
- Software and electronics are fast. Mechanical systems are slow. Low-pass filter a lot.
- How to determine angles
- How to approach the puck without compromising line-of-sight

SOFTWARE: DEBUG EARLY, OFTEN, AND EFFICIENTLY
- Constellation
- Puck (or just an IR emitter!)
- USB Debugging
- USB Debugging + Wireless comm
- Collision tests

LEARN TO DEBUG
- Comment everything!
- Wrong variable type
- Finding the source of electrical failure
- Leave space for debugging equipment

TIME MANAGEMENT: PLAN
- Set concrete goals
- Pick a day every week to work until the goal is reached
- If a goal is reached early, begin work on the next goal
- There is ALWAYS a next goal!
- Compromise on the fly---wisely---but only as needed!

TIME MANAGEMENT: CHOOSE
- Manufacturing technique (print, machine, cut, order, other)
- Light vs heavy
- Smart vs dumb
- Fast vs accurate
- Analog vs digital
- A single awesome goalie can rule the world

TIME MANAGEMENT: RESTRAIN
- Mecanum wheels
- Massive motors
- Extra weight

TIME MANAGEMENT: WASTE
- Soldering perfboards
- Creating 38 different sheet goods layers
- Creating connections
- Creating wheels
- Status LEDs
- Not labelling EVERYTHING
- Working in cluttered environments

TIME MANAGEMENT: SAVE
- Unsupervised construction (delegation)
  . 3d printing
  . PCB fabrication

TIME MANAGEMENT: BUY EARLY
- Motor drivers
- Wheels
- PCBs
- Jerseys
- Battery and LED connection wires

TIME MANAGEMENT: AESTHETICS
- No.
- Let functionality rule ALWAYS
- Use a drill, a dremel, or duct tape if it works and saves time

TECH YES
- Li-po batteries
- 90-degree motors

TECH NO
- Sticky wheels (crumble and/or rip off)
- Large motor driver boards
- Long jumper wires

WHAT WOULD BE DIFFERENT?
- Shield-style PCB which fits M2 AND motor driver
- More channels between layers for wires, etc
- Create sensors very early, using assembly line techniques
