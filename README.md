
JANUS is an epistemically governed computational architecture for reasoning over evolving systems and controlling the transition from observation and inference to evidence-based action.

JANUS operates on information about systems whose state may change over time. It provides a structured separation between observation, state estimation, inference, hypothesis, evidence, belief, authorization, and execution, so that computational conclusions can be evaluated according to their epistemic status before they acquire operational consequences.

At its core, JANUS treats computation as a sequence of constrained epistemic and operational transitions:

Observation → State Representation → Inference → Hypothesis → Evidence → Belief → Authorization → Execution → Outcome → Evidence Update

Each transition has a defined role and scope. No transition is assumed to imply another automatically.

The architecture therefore distinguishes:

Capability ≠ Authority ≠ Authorization ≠ Execution

and maintains explicit separation between what a system observes, what it estimates, what it infers, what it hypothesizes, what the available evidence supports, and what it is authorized to do.

JANUS combines mathematical modeling of evolving systems with epistemic evaluation and controlled execution. Its research program includes dynamic-system modeling, state and parameter estimation, uncertainty handling, hypothesis evaluation, evidence tracking, cognitive processing, governance, authorization, controlled execution, retrospective evaluation, and controlled adaptation.

The architecture is designed so that operational authority is not derived merely from computational capability or predictive output. An internally generated conclusion can therefore remain a hypothesis, require additional evidence, be evaluated in simulation, or be denied authorization rather than automatically becoming an external action.

JANUS is developed as an empirically testable architecture. Mathematical formulations, implementations, and behavioral claims are evaluated separately, with experimental results assigned explicit epistemic status according to their validation scope.

Where a mechanism is supported by evidence, its status and conditions of validation are documented. Where evidence is incomplete, the mechanism remains a research hypothesis or open direction. Where an experimental claim fails its predefined criterion, it is retained as a falsified result rather than promoted into the architecture's established knowledge.

The central research problem of JANUS can therefore be stated simply:

> How can a computational system move from partial observations about an evolving world to justified action while preserving the distinction between what is observed, what is inferred, what is supported by evidence, and what is authorized?



That is the core definition of JANUS.
```

---

## The question

A single measurement says where a system is now.
A trajectory starts to say how it got there.

If you watch a person, a grid, a market, a body, or a network across time, you are not holding a pile of independent numbers. You are holding fragments of a process that is still happening.

The first question is not *what is the value*.
It is *what kind of motion produced this value*.

The next question is harder:

**What can actually be known from a partial trajectory — and what, if anything, should be allowed to happen because of that knowledge?**

JANUS is a research and engineering programme built around that second question.

---

## Public definition

JANUS is an epistemically governed execution architecture.

It keeps five things from collapsing into one another:

- **cognition** — the ability to infer, predict, hypothesize, propose
- **epistemic state** — what is observed, inferred, guessed, contradicted, or still open
- **trust / maturity** — how far a representation has earned operational confidence
- **authorization** — whether a specific proposal may become real
- **execution** — the act that leaves the model and touches the world

A model may be fluent.
It may be calibrated.
It may even be right.

None of that is permission.

---

## Between a human and a model

The language model is not the operator.
The human is not a prompt-shaped accessory to the model.
JANUS is the layer that refuses to let those two roles collapse.

```
Human intent
    → model possibilities
        → JANUS
            → permission, delay, simulation, or refusal
                → world
```

The model is extraordinary at generating what *could* be said or done.
The human is the only party who can mean it.
Something has to stand between them when “could” starts to look like “may”.

That something is not another chatbot.

It is a stance:

- the model proposes; it does not inherit the right to execute  
- the human can ask, constrain, accept, or revoke; they are not required to audit a raw token stream in order to remain responsible  
- fluency is treated as a candidate, not as a decision  
- a beautiful plan can still be unauthorized  
- a weak plan can still be useful — as a hypothesis, a warning, or a simulation  

Without an intermediary, two failures become easy.

The model acts as if speech were already agency.  
The human acts as if a fluent answer were already a warrant.

JANUS is the hypothesis that those failures are architectural, not moral.

Put a governance surface between person and model, and the conversation changes shape. The human is no longer negotiating with a soliloquy. The model is no longer one tool-call away from the world. What crosses the gap has to survive a question that neither party likes:

**Is this still language — or is this already an act?**

If it is still language, let it be rich.
If it is already an act, it needs more than eloquence.

That is the role.

Not to replace the human.
Not to tame the model into silence.
To keep the human as the source of intent, the model as the source of possibility, and the crossing between them from happening by accident.

---

## Why the ordinary loop is not enough

The usual agent pattern is short:

```
Observation → Model → Tool → Outcome
```

That loop is powerful. It is also easy to over-trust.

A system can be capable and still uncertain.
Confident and still wrong.
Well-informed and still unauthorized.
Authorized and still acting on a state that has already moved.
Able to execute and still without a warrant to do so.

JANUS is interested in the missing layer between *a possibility* and *a permitted act*.

Not as a slogan.
As an architectural problem: how to keep those two from becoming the same event.

---

## A working intuition

Imagine a system that watches something change.

It can reconstruct a state.
It can guess the next state.
It can invent an intervention.

The interesting moment is not the invention.

The interesting moment is the pause:

- Is this still an observation, or already a story?
- Is this a hypothesis, or a belief?
- Has the world changed faster than the model?
- Does a better prediction entitle the system to a stronger action?
- If the evidence is thin, should the system act, wait, simulate, or admit that it does not know enough?

JANUS is an attempt to make that pause first-class.

The working hypothesis is simple:

**A system that can tell those questions apart will be able to act on more kinds of living processes — not because it is more aggressive, but because it knows when not to be.**

---

## From a moving observation to a governed act

The work did not begin as a monument.

It began with repeated observation of experience over time. A point became a trajectory. A trajectory became dynamics. Dynamics made uncertainty visible. Uncertainty made knowledge a problem. Knowledge made decision a problem. Decision asked what a system should do when it does not know enough.

That sequence is the public spine:

**observation → trajectory → dynamics → uncertainty → evidence → knowledge → decision → execution**

Each stage opens the next.

The human case was the beginning, not the boundary.
The same difficulty appears in physiology, industry, infrastructure, markets, networks, and any computational system that can observe, interpret, and act.

A person is a dynamical system.
So is a plant.
So is a grid that can cascade.
So is an agent that can call a tool.

The object is not one dataset.
It is a partially observed process that will not sit still.

---

## What JANUS is trying to hold apart

| This | is not automatically | that |
|------|----------------------|------|
| Observation | | Knowledge |
| Hypothesis | | Belief |
| Prediction | | Understanding |
| Capability | | Authority |
| Learning | | Self-promotion |
| Proposal | | Action |
| Maturity | | Trust |
| Authorization | | Execution |

These distinctions are the public architecture.

They are also the programme: can a running system keep them intact while it estimates, predicts, proposes, sometimes acts, and then remembers what happened — including when it was wrong?

---

## Ambition

The ambition is not a system that always acts.

The ambition is a system that gets better at recognising:

when to act,
when to wait,
when to try the act only as a simulation,
and when to say that the present picture is not a sufficient basis for touching the world.

If that stance can be made stable — across different kinds of time series, different kinds of uncertainty, different kinds of proposed action — then the same architecture becomes relevant far beyond any single domain.

That is the bet.

The bet travels. The next sections say where, and where it stops being the same conversation.

---

## Possibilities

JANUS is not only a set of distinctions. It is a way of standing next to a living process and asking what kind of companion a model is allowed to be.

At the smallest human scale it can be imagined as a personal intermediary: not a secretary that executes every fluent plan, but an agent that stays with *your* days. It would watch how your mood, attention, sleep, language, and context move together — not as a diagnosis, and not as a score that replaces you. As a map of *this person over time*. When a language model then proposes “send this”, “change that”, “decide now”, the proposal would have to pass through a picture of whether today is like the last ten days, or whether something in you has already shifted.

That is within-person mapping.

Most systems compare you to a crowd.  
A within-person view compares you to your own recent trajectory: the same body, the same week, the same pressures, the same recoveries. It is the difference between “people like this usually…” and “you, yesterday to today”.

The interesting object is not a static profile.  
It is a moving interior: affect that rises and falls, a note written on a platform at midnight, a heart-rate that does not match the story you told yourself, a stretch of days that look calm until they do not. A model can talk about all of that. An intermediary would have to know which of those talks is still language, and which would already change the day.

From there the same stance can travel — still as possibility, still as research direction — into other disciplines, because the shape of the problem repeats.

| Field | What is moving | What an intermediary would be for |
|-------|----------------|-----------------------------------|
| Lived experience / EMA-style observation | Mood, context, sleep, language, social load | A companion that maps *your* change, not a crowd average |
| Physiology | Signals that only mean something across hours and nights | Separating a transient spike from a shift in the process |
| Clinical and recovery-oriented observation | Slow trajectories, setbacks, coping | Keeping a proposal from outrunning the actual week |
| Education and attention | Focus, delay, exam pressure, notes | Distinguishing a bad hour from a changing pattern |
| Industrial process | Drift, wear, departure from expected behaviour | Watching before intervening |
| Energy and infrastructure | Load, cascade, overload | Not treating a local flicker as a licence to reconfigure the whole |
| Transport | Flow, shock, weather, delay | Acting on a corridor without pretending the city is one number |
| Markets and supply | Regime, volatility, dependence | Prediction that does not silently become an order |
| Networks and security | Anomaly, intrusion, noisy alert | Analysis that is not already a response |
| Science | Hypothesis, instrument, incomplete evidence | A lab assistant that cannot promote a guess into an experiment by eloquence |
| Personal tool-using agents | Mail, calendar, files, browsing, home | An agent that belongs to you, and does not spend your world because it can |

The personal agent is the honest first picture.

Not a bank.
Not a hospital.
Not a grid operator.

A system that sits between you and a language model while you live a life: drafts, reminders, research, messages, plans, “should I send this”, “is this week different”, “don’t do anything until I look”. That is already a serious use. It is also the right scale at which to learn whether the pause is real.

A bank, a clinic, a control room — those are the same *kind* of question with a different price of being wrong. There the intermediary would stand between a model that can propose a transfer, a titration, a breaker action, and a world that will not undo the act for free. The public stance is that those domains are visible from here. They are not the starting costume.

---

## A descriptive boundary

There is a line that the writing should not pretend to cross.

**Same question, different room.**

In a personal agent the world is your inbox, your notes, your evening.  
If the intermediary waits, you wait with it.  
If it is wrong, the cost is usually recoverable.

In a bank, a ward, or a transmission desk the world is other people’s money, bodies, or lights.  
Waiting is still a decision.  
Acting is never only language.

So the boundary is not “JANUS cannot be imagined there”.  
The boundary is: a picture of a personal agent is not a picture of a certified institution. A map of one person’s week is not a credit model. A recovery-oriented trajectory is not a medical device. A cascade metaphor is not a licence to switch a grid. A fluent proposal about a market is not an order.

Capabilities, as they are spoken here, are rooms the architecture can be *pointed at*.  
They are not rooms it has been handed the keys to.

The first room is closer to:

*an agent of your own, standing between you and a model, mapping how you change, and asking whether today’s proposal is still only words.*

The later rooms are larger.  
They remain later until the evidence says they are not.

---

## What this repository is

This is the public research surface of JANUS.

It is here so the question, the vocabulary, and the stance can be inspected.

Implementation-specific mechanisms, proprietary parameters, internal execution protocols, and reconstruction details are intentionally withheld from the public layer.

[IP_DISCLOSURE_NOTICE.md](IP_DISCLOSURE_NOTICE.md) · [PUBLICATION_BOUNDARY.md](PUBLICATION_BOUNDARY.md) · [SECURITY.md](SECURITY.md)

---

## Status

Selected execution-integrity behaviours have been tested on a documented local reference runtime.
The broader empirical boundary is still open.
Negative results are kept.

[RESEARCH_STATUS.md](RESEARCH_STATUS.md) · [PUBLIC_CLAIM_REGISTER.md](PUBLIC_CLAIM_REGISTER.md) · [docs/negative-results.md](docs/negative-results.md)

---

## What JANUS is not

Not a language model.
Not a prompt trick.
Not just another agent loop.
Not a promise that the world will be safe if you turn it on.

It is an architecture for keeping reasoning and permission from becoming the same thing.

---

## Read next

| | |
|--|--|
| [docs/from-observation-to-action.md](docs/from-observation-to-action.md) | The public essay |
| [docs/principles.md](docs/principles.md) | The ten distinctions |
| [docs/architecture.md](docs/architecture.md) | Public architecture view |
| [docs/epistemic-model.md](docs/epistemic-model.md) | States of knowing |
| [docs/governance.md](docs/governance.md) | From proposal to permission |
| [docs/applications.md](docs/applications.md) | Where the question travels |
| [docs/faq.md](docs/faq.md) | Short answers |
| [docs/limitations.md](docs/limitations.md) | Limits |

---

See [CITATION.cff](CITATION.cff) and [LICENSE](LICENSE).

*A system does not become entitled only because it becomes more capable.*
*It becomes interesting when it can tell those two apart.*
