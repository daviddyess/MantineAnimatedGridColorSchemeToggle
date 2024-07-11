# MantineAnimatedGridColorSchemeToggle
Creates an animated effect similar to the Suits intro while changing color schemes in Mantine.

This is a first draft, so there is room for improvements. Any contributions are welcome. I'd like to add other animations, so feel free to submit pull requests if you create a new transition and want me to add it as well.

Created with assistance from Claude AI

## ColorSchemeToggle component

### Props

- `duration` - length of animation
- `fadeOutDuration` - length of fade out after animation
- `transition` - if false it's just a regular color scheme toggle with no animation

### Example usage:

```javascript
import { ColorSchemeToggle } from './ColorScheme/ColorSchemeToggle';

...
return (
    <ColorSchemeToggle
        duration={2000}
        fadeOutDuration={6000}
        transition
    />
);
```

## Customization

`TimedGridOverlay` accepts props of `duration` (animation time), `fadeOutDuration` (fade out time), `onFadeOutStart` (function to call when the fade out starts), and `onFadeOutEnd` (function to call when the fade out ends)
