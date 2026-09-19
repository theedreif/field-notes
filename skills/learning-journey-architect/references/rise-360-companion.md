# Rise 360 HTML Build — Companion Skill

## Role separation

**Learning Journey Architect / XMAL** owns learning architecture.

It determines:
- required capability;
- learner journey;
- media/touchpoints;
- practice;
- friction;
- evidence;
- transfer.

**rise-360-html-build** owns implementation of custom interactions inside Articulate Rise 360.

The supplied companion skill defines these engineering concerns:
- delivery path selection;
- build specification;
- sandboxed iframe constraints;
- responsive behavior;
- accessibility;
- completion messaging;
- packaging;
- QA.

## Key production principles inherited from the supplied skill

For Rise custom code:
- choose deliberately among Add Code, uploaded project ZIP, iframe embed, and post-export patch;
- design for the sandboxed iframe rather than a normal webpage;
- avoid external dependencies when packaging custom code;
- use transparent backgrounds and let Rise control surrounding spacing;
- design for known iframe height/internal scrolling constraints;
- make interactions usable down to narrow mobile widths;
- make keyboard and screen-reader behavior explicit;
- wire completion only when the learner has actually completed the required interaction;
- QA before handoff.

## Architectural handoff

Learning Journey Architect should produce an interaction brief before the implementation skill runs.

Minimum handoff:
1. capability/objective served;
2. learner action;
3. state changes;
4. feedback/consequence;
5. completion condition;
6. evidence captured;
7. responsive behavior;
8. accessibility requirement;
9. visual relationship to the surrounding journey.

The production skill then engineers the component.

## Principle

**Methodology chooses the experience. Technology implements it.**
