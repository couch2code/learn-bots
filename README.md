# Learn Bots

Lesson 1

---

### Teachers

* Mr Tom
* Ms Alex
* Mr Lucas

---

### Rules

* Be Cool
* Raise your hand when you want to speak or need help.
* If you are stuck in a challenge, ask your neighbor, ask google, ask the teacher

---

### Lesson Format

Each lesson will last about an hour, and the format will go as follows:

* Introduce something new to learn.
* Watch me apply the topic on the projector.
* Exercises to practice the concept.

---

! http://i.giphy.com/XlhzCl8UQ3MaI.gif

---

### Lets get started

* Stand up
* Reach the Sky
* Touch your toes
* Run in place
* Take your seat

---

### Quick Overview

---

* What is the internet?
* What is a web site?
* What is HTML?
* What is CSS?
* What is JavaScript?
* What is a command?

---

### Learn Bots

Today we are going to learn how to use code to control things. This is sometimes
called the internet of things.

---

# Lesson 1

Functions

---

# Demo

Lets write code to turn on a light.

---

# Exercises

---

### Exercise 1 - Hello World Light

In this exercise we will make a light blink. Use the J5 Chrome application to
connect to your nodebot.

---

```
var redLightStatus = false
var redLight = new five.Led(13)

/* add commands here */
function toggleLight (cmd) {
  redLight[cmd]()
}

/* end of commands */

```

---

```
toggleLight('on')
toggleLight('off')
```

---

## Lesson 2

More Functions

---

# Demo

---

```
function move (cmd) {
  if (cmd === 'forward') {
    right.cw()
    left.ccw()
  } else if (cmd === 'backward') {
    right.ccw()
    left.cw()
  } else {
    right.stop()
    left.stop()
  }
}
```

---

# Exercises

---

### Lets make our bot move

```
function move (cmd) {
  if (cmd === 'forward') {
    right.cw()
    left.ccw()
  } else if (cmd === 'backward') {
    right.ccw()
    left.cw()
  } else {
    right.stop()
    left.stop()
  }
}
```

---

## Lesson 3

More functions

---

# Demo

---

```
function turn (direction) {
  if (direction === 'left') {
    left.ccw()
    right.ccw()
  } else if (direction === 'right') {
    left.cw()
    right.cw()
  }
}
```

---

### Exercises

---

### Exercise

```
function turn (direction) {
  if (direction === 'left') {
    left.ccw()
    right.ccw()
  } else if (direction === 'right') {
    left.cw()
    right.cw()
  }
}
```
---

## Lesson 4

Time to decorate your bot!

---

## Lesson 5

Battlebots
