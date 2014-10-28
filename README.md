# sass.animations
> A glob of sass animations.

## Installation

```
$ bower install aglobof-sass.animations
```
 
## Usage
 
Include the partial in your root sass file.

```scss
@import "bower_components/aglobof-sass.animations/animate";
```
 
Call animations all over the place like a boss
 
```scss
@include keyframe(load-in-slow) {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.content {
  @include animation(load-in-slow, initial, 1s, ease-in, 1);
}
```
