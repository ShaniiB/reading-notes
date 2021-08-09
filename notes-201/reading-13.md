# INDEX.201-NOTES__//READING-13

## __subject//___CSS-Transition
For a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the <b>:hover</b>, <b>:focus</b>, <b>:active</b>, and <b>:target pseudo-classes</b>.

There are <b>four transition</b> related properties in total, including <b>transition-property</b>, <b>transition-duration</b>, <b>transition-timing-function</b>, and <b>transition-delay</b>. Not all of these are required to build a transition, with the first three are the most popular.

## __subject//___Transitional Properties

It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. <b>Colors</b>, <b>font sizes</b>, and the alike may be <b>transitioned</b> from one value to another as they have recognizable values in-between one another. The <b>display property</b>, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.