# mta-parametric
Parametric equation visualizer for MTA:SA - because why not?

## Purpose
A generic tool that allows the user to visualize parametric equations in the 3D Grand Theft Auto world - combining math and shooting people.

## Use
Input follows the following format, with expressions in terms of the variable t:

    /pm (expx) (expy) (expz)
    
<br>
For example:

    /pm sin(t) cos(t) t
    
is the definition of a helix of a radius of 5 meters, at the center of the map.

<br>
To reset the display, use the command

    /pm
    
without arguments.

## Examples:
### Helix:

    /pm sin(t) cos(t) t
    
### Spiral

    /pm t*sin(t) t*cos(t) t

## Credits
This resource uses a modified version of the [EvalExpression](https://github.com/jbp4444/EvalExpression) mathematical expression evaluator by [@jbp4444](https://github.com/jbp4444/) in order to calculate the values for its data points.
