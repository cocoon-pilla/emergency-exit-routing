# Emergency exit routing

A simple script to give a designer an effective routing of exiting from one floor through a Rhino model.

## Instructions

- Define floors in the layer 'floors'
- Define potential openings in the layer 'openings
- Select floors and openings
- Connect the EmergencyRoute component to 
  - integer denoting the number of hours you want to survive for.
  - arrays for the floors and the openings
- Use the output to create nurbs lining the potential routes, ordered by escape time.

## Contributing

This is very much a work in process, feel free to join the github group and contribute your fixes and extensions!
