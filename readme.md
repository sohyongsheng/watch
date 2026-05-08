User guide
==========

Sounds
------

All sounds have a tempo of 60 beats per minute, and the same pitch.

### Beep ###

The beep is a sixteenth note. This is the shortest sound.

### Double beep ###

The double beep is a pair of sixteenth notes, i.e. 2 beeps
consecutively.

Buttons
-------

There are 3 buttons: `set`, `next` and `light`. The `set` and `next`
buttons are at the sides of the case. The `light` button is at the front
of the case below the crystal.

Each button registers 

- 2 actions: press and release.
- 2 moments: when the event happens, and when the operation is
  confirmed.

Operations
----------

### Hold delay ###

This is the minimum duration that the user needs to hold a button to
register the operation as a long press instead of a short press.

### Press ###

This is a short press.

1. Press the button. There will be a beep. This records the event.

2. Release the button *before* the hold delay. This confirms the operation
   as a short press.

### Hold ###

This is a long press.

1. Press the button. There will be a beep. This records the event.

2. Release the button *after* the hold delay. There will be a double
   beep. This confirms the operation as a long press.



