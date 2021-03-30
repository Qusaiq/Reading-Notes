# CSS Transforms, Transitions, and Animations
.
### ***transform***

**The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.**

#### Syntax
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

- The ``` transform ``` property may be specified as either the keyword value ``` none ``` or as one or more ``` <transform-function> ``` values.
If ``` perspective() ``` is one of multiple function values, it must be listed first.
- The transform property applies a 2D or 3D transformation to an element.

### ***Transitions***

***CSS transitions allows you to change property values smoothly, over a given duration.***

#### How to Use CSS Transitions?

To create a transition effect, you must specify two things:
1. the CSS property you want to add an effect to
2. the duration of the effect
**Note:** If the duration part is not specified, the transition will have no effect, because the default value is 0.

### Syntax
```
/* Apply to 1 property */
/* property name | duration */
transition: margin-right 4s;

/* property name | duration | delay */
transition: margin-right 4s 1s;

/* property name | duration | easing function */
transition: margin-right 4s ease-in-out;

/* property name | duration | easing function | delay */
transition: margin-right 4s ease-in-out 1s;

/* Apply to 2 properties */
transition: margin-right 4s, color 1s;

/* Apply to all changed properties */
transition: all 0.5s ease-out;

/* Global values */
transition: inherit;
transition: initial;
transition: unset;
```

### ***Animations***

***An animation lets an element gradually change from one style to another.***

- You can change as many CSS properties you want, as many times you want.
- To use CSS animation, you must first specify some keyframes for the animation.
- Keyframes hold what styles the element will have at certain times.

#### The ```@keyframes``` Rule
When you specify CSS styles inside the ```@keyframes``` rule, the animation will gradually change from the current style to the new style at certain times.

**Note** To get an animation to work, you must bind the animation to an element.