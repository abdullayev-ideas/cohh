# COHH - Clock Of Human History


## Purpose

COHH makes years in history easier for **history learners** to remember. It does this by turning each year into a picture you can see, the way an analog clock shows time.

### The problem

Years in history are just digits: 441, 572, 1453. You can't *feel* them. When you misremember one, it's easy to swap or mix up a digit. Then you're off by a few decades, a few centuries, or even worse, and nothing tells you that something is wrong. Many history learners struggle with this.

### The idea

Nobody reads a wall clock by working out the numbers. You glance at it and just *know* it's "almost half past three", because you remember where the hands are, not the digits.

COHH gives years in history that same kind of face:

- **Shape instead of digits.** Each year becomes a picture: where the satellite sits and where each hand points. Our memory for pictures and places is much stronger than our memory for abstract numbers. This is the same trick behind classic mnemonic techniques such as the memory palace.
- **Two ways to remember.** You learn a year both as a number and as an image. When one fades, the other can bring it back.
- **Mistakes you can see.** On a clock face, being off by a century isn't a quiet digit swap. It's a hand pointing at a clearly different spot. If the picture in your head doesn't match the event, you notice.
- **Feeling distance in time.** Two events that are close in time look alike. Events that are far apart look different. You can sense how much time passed between them at a glance, without doing any math.

The goal isn't to replace numbers, but to give them a shape that you can see, feel, and remember.


## Shape

- `circular`, just like a regular clock
- `10` numbers instead of 12
- `3` hands or `2` hands, just like a regular clock
- the top number is `0`, not 10 or 12
- the bottom number is `5`, not 6


## Hands

Logically and functionally, they are pretty much the same as on a regular clock.


### hand100

- this is the equivalent of the hour hand on a regular clock
- one step means 100 years have passed
- a full 10 steps mean 1000 years have passed


### hand10

- this is the equivalent of the minute hand on a regular clock
- one step means 10 years have passed
- a full 10 steps mean 100 years have passed


### hand1

- this is the equivalent of the second hand on a regular clock
- one step means 1 year has passed
- a full 10 steps mean 10 years have passed


## Clock Satellite

- it looks like a piece of a circular ring (imagine a slice of a circle with most of its pointy part removed)
- it shows a number referring to the millennium, and that number can be negative too
- when the satellite is above the horizontal diameter, the bottom of its text faces toward the center of the circle/clock
- when the satellite is below the horizontal diameter, the bottom of its text faces away from the center of the circle/clock
