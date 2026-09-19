# Worked Example — Maritime C2 Pre-Launch Journey

## Terminal Learning Objective

Given an operations terminal, telemetry link, and live craft in wet berth, the operator will execute the pre-launch satellite/C2 link verification protocol within 8 minutes, achieving zero protocol omissions according to the SOP rubric.

## Enabling Objectives

- EO 1: Verify craft DC bus voltage is within operating envelope (24–28V).
- EO 2: Establish primary RF line-of-sight command link.
- EO 3: Initialize satellite telemetry secondary link and verify cryptographic handshake.
- EO 4: Execute emergency link-loss autonomous failsafe verification test.

## ISD task decomposition

EO 1 — Check DC bus telemetry using console GUI / Bus Monitor. Example criterion: voltage within defined operating envelope. Error consequence: inadequate bus power can threaten launch reliability.

EO 2 — Power RF radio and verify carrier lock using RF Control Panel. Example criteria supplied in the scenario: SNR ≥18 dB and ping latency <40 ms. Error consequence: loss of commandability beyond dock boundary.

EO 3 — Handshake SATCOM and cycle crypto key using Comms Suite / Crypto Terminal. Criterion: authenticated key state and no parity errors. Error consequence: communications failure.

EO 4 — Trigger manual ping cutoff using failsafe control. Criterion supplied in the scenario: craft enters hold state within 3.0 seconds. Error consequence: uncontrolled asset behavior in an active channel.

Treat all operational thresholds as scenario/source values requiring authoritative verification before real-world use.

## LXD translation

Learner context:
- rushed;
- susceptible to cognitive tunneling;
- exposed to ambient dock noise and communications chatter;
- required to work across multiple software panels;
- at risk of memorizing clicks rather than developing situational awareness.

## Integrated journey

### Orientation & awareness
Target: EOs 1–4 and system architecture.

Experience: short interactive cause/effect mental model showing why link verification matters.

### Skill acquisition & mechanics
Target: EOs 1–3.

Experience: guided simulation with scaffolding and explanation of sequence logic.

### High-stress sandbox
Target: EO 3 + EO 4.

Experience: branching operational scenario with faults, time pressure, and competing signals.

### Transfer to live deck
Target: complete TLO.

Experience: live execution supported by a compact field checklist/status aid.

## Design lesson

**Mental model → deliberate practice → high-stress simulation → job-aid-supported live execution**

The ISD blueprint protects technical fidelity.

The LXD journey manages cognitive load, usability, motivation, and transfer.

The field evaluation asks whether the required behavior persists in operations.
