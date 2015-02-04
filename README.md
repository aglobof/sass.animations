# sass.animations
> A glob of sass animation mixins

## Installation

**via bower**

```shell
$ bower install aglobof-sass.animations --save-dev
```

**via npm**

```shell
$ npm install aglobof-sass.animations --save-dev
```
 
## Usage
 
Include a partial in your root sass file.

```scss
@import "bower_components/aglobof-sass.animations/animation";
```

Or, glob all the partials

```scss
@import "bower_components/aglobof-sass.anitmations/glob";
```

### Animate

Call animations all over the place like a boss
 
```scss
@include keyframe(load-in-slow) {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.content {
  @include animation(load-in-slow, 1s, ease-in-out);
}
```

### Transform

TBD

### Translate

TBD
