# Android-SVG-path-rendering

This simple class allows Android Application to draw SVG paths. This class is still a WIP.

Any help would be appreciated.

Based on original [Nicolas](https://stackoverflow.com/users/5288316/nicolas) code

## Usage

```
Drawable drawable = VectorDrawableCreator.getVectorDrawable(this, 24, 24, 100f, 100f, true, 0f, 0f, listOf(VectorDrawableCreator.PathData(customPath, Color.RED, Color.BLACK)))
```

## Feature

Currently attributes supported :
- height
- width
- viewportHeight
- viewportWidth
- fillColor
- pathData
- strokeWidth
- strokeColor

The class draws only 1 custom path
