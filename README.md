# SPWN-speed

A simple function to get the "blocks per second" of any speed portal.

## Example

```spwn
speed = import 'speed.spwn'

$.print(speed(1/2))
$.print(speed(1))
$.print(speed(2))
$.print(speed(3))
$.print(speed(4))
```

## Disclamers

This gets quite precise values of the speed portals (run `spwn build test.spwn -c` to see the errors),
but if there are in-between values, they may or may not match the actual numbers from GD (if those speeds existed).
