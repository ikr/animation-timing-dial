# About

The `animation-timing-dial` is a GUI control (widget) for adjusting the flow of a graphical
animation. The widget looks like a round dial with a small disc looping over its circumference. If
the user does nothing, the disc will be looping clockwise, moving with constant speed. That
corresponds to the normal flow of the animation. The user can change the animation flow by dragging
the disc forward or backwards along the dial's circumference, making the animation go forward or
backwards as fast or slow as they like.

Then, the dial circumference has evenly distributed notches. Every time the disc meets a notch, a
new animation frame gets displayed. The frequency of notches can be adjusted by the user as well. To
do so, they need to rotate the dial with 2 fingers: clockwise rotation puts more notches onto the
dial, and counterclockwise rotation reduces the notch count.

A single tap on the dial will pause or resume the disc movement.

# API

A stream of frame numbers

# Packaging

Web component?

# Status

Work in progress

# License

[MIT](./blob/master/LICENSE)
