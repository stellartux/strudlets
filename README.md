# strudlets

## `roman`

Use Roman numeral harmony notation. Use `.scale("X:chromatic")` to set the one chord.

```javascript
const { roman } = await import('https://stellartux.github.io/strudlets/lib.js')

$: roman("<I V vi IV>").scale("C:chromatic").note().sound("piano")
```

## `colorwheel`

Add colours to note values with a palette based on the circle of fifths.

## `lerp(min, max)`, `qerp(min, max)`

Linearly/quadratically interpolate between values.
