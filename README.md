# Sass Animations

> A glob of Sass animations.

## Install

`bower install aglobof-sass.animations`
 
## Usage
 
Include the partial in your root sass file.

```
// Sass Mixin Includes
@include '../lib/to/bower/aglobof-sass.animations/animate'
```
 
Call animations all over the place like a boss
 
```
@include keyframe(load-in-slow) {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.content {
  @include animation(load-in-slow, initial, 1s, ease-in, 1);
}
```
