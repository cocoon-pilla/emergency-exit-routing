# Emergency exit routing

A simple script to give a designer an effective routing of exiting from one floor through a Rhino model.

<img width="893" alt="path" src="https://cloud.githubusercontent.com/assets/20371914/16713068/9fb44f2c-4693-11e6-94dd-7cd7ae9ce095.png">

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
