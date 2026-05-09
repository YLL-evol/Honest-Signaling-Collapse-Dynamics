# Honest-Signaling-Collapse-Dynamics

An agent-based evolutionary simulation inspired by the classical honest signaling theory of Amotz Zahavi.

This project explores a simple question:

> How long can an honest signaling system remain stable before collapsing under cheating pressure?

The model combines:

* costly signaling
* cheating strategies
* receiver learning
* social reputation
* scale-free social networks
* stochastic mate choice
* evolutionary inheritance

Agents compete using either:

* honest costly signals
* low-cost deceptive signals (“hollow stones”)

Receivers gradually learn to detect deception, while social structure shapes the spread of trust and cheating.

The main observable is:

## Signal Collapse Time

Defined as the first generation where:

```python
Trust < threshold
```

This project was motivated by extending Zahavi’s classical static honest signaling framework into a temporal and networked evolutionary system.

Instead of asking:

> Why are costly signals honest?

the project asks:

> How long does honesty survive once cheap imitation emerges?

## Features

* Agent-based evolutionary simulation
* Scale-free signaling networks
* Dynamic trust collapse
* Receiver adaptation
* Parameter sweeps
* Oscillatory signaling dynamics
* Collapse-time analysis

## Dependencies

* Python 3.11
* numpy
* scipy
* matplotlib
* networkx
* jupyter

## Future Directions

* Bayesian receivers
* Multi-channel signaling
* AI-generated signaling inflation
* Dynamic environments
* Empirical calibration

## Conceptual Background

Inspired by:

* Amotz Zahavi — Handicap Principle
* signaling theory
* cultural evolution
* information ecology
* evolutionary game theory
