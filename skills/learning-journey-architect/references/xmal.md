# XMAL — Experience Model for Adaptive Learning

## Canonical implementation

https://edcreates.s3.us-west-1.amazonaws.com/xmandash.html

The canonical XMAL example is a responsive instructional-design control panel organized as vertically stacked interactive cards. Its experience direction is closer to modern scrolling web behavior than a fixed PowerPoint-like slide deck.

## XMAL principle

**The learner moves through meaning, not slides.**

Prefer:

**SCROLL → ENCOUNTER → INTERACT → DECIDE → CONSEQUENCE → CONTINUE**

over an automatic:

**SCREEN → NEXT → SCREEN → NEXT → QUIZ**

## What XMAL is not

XMAL is not endless passive scrolling.

A scroll journey should contain meaningful changes of state:
- orientation;
- reveal;
- comparison;
- interaction;
- decision;
- consequence;
- practice;
- reflection;
- evidence;
- transfer.

## Architecture

A typical XMAL journey can move through:

**ARRIVE → ORIENT → BUILD MENTAL MODEL → NOTICE → PRACTICE → DECIDE → EXPERIENCE CONSEQUENCE → RETRY UNDER FRICTION → TRANSFER → PROVE**

## Interaction rule

Use interaction only when it changes cognition or behavior.

Avoid decorative click-to-reveal patterns where scrolling or clear prose would be more usable.

## Bounded experiences

Some activities should temporarily become bounded:
- software simulation;
- operational console;
- branching decision;
- timed scenario;
- procedural rehearsal;
- assessment.

Return the learner to the journey when the bounded activity is complete.

## Responsive rule

Design for vertical continuity and narrow screens from the beginning. Do not simply shrink a desktop slide deck onto a phone.
