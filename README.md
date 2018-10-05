# random.js

A helper library for Math.random().

## Random.range(min, max)

Generates a number between min and max.

```
// Give me a number between 0 and 1.
var number = Random.range(0, 1)
```

## Random.rangeInt(min, max)

Generates an integer between min and max.

```
// Give me an integer between 0 and 1.
var int = Random.rangeInt(0, 1)
```

## Random.chance(percentage)

Has a ```percentage``` chance of returning true.

```
// Give me a 50% chance of returning true.
var fiftyFifty = Random.chance(50);

// Give me a 100% chance of returning true.
var forSure = Random.chance(100);
```
