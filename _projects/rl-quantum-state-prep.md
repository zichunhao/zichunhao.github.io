---
layout: page
title: Reinforcement Learning for Quantum State Preparation
description: The final project I co-designed for Caltech Ph 22, Computational Physics Laboratory III
permalink: /projects/rl-quantum-state-prep/
importance: 1
category: teaching
---

For the Spring 2026 offering of Caltech's Ph 22, Computational Physics Laboratory III, I was one of the two teaching assistants who designed and built the final project, in which students train reinforcement learning agents to control a quantum system.

The physics setting is the [Tavis–Cummings model](https://en.wikipedia.org/wiki/Tavis%E2%80%93Cummings_model), the canonical [cavity quantum electrodynamics](https://en.wikipedia.org/wiki/Cavity_quantum_electrodynamics) system of atoms coupled to an optical cavity. The agent chooses laser pulses, each with a duration, an amplitude, and a phase. The environment integrates the [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) for each pulse and rewards the agent for steering the system toward a target quantum state such as a [Fock state](https://en.wikipedia.org/wiki/Fock_state), a [coherent state](https://en.wikipedia.org/wiki/Coherent_state), a [Bell state](https://en.wikipedia.org/wiki/Bell_state), or a [Schrödinger cat state](https://en.wikipedia.org/wiki/Cat_state).

I built the [Gymnasium](https://gymnasium.farama.org/) environment wrapping the physics simulator, the shaped reward design, the graded ladder of target states, and the baseline policies students must beat. Students implement [REINFORCE](https://link.springer.com/article/10.1007/BF00992696) from scratch and can compare it against [PPO](https://arxiv.org/abs/1707.06347), [SAC](https://arxiv.org/abs/1801.01290), and [TQC](https://arxiv.org/abs/2005.04269) through [Stable-Baselines3](https://stable-baselines3.readthedocs.io/), across MLP, LSTM, and Transformer policies. The project also covers experimental rigor through multi-seed evaluation, reward ablations, and a transfer learning recipe that pretrains on an easier target before finetuning on the hardest non-Gaussian cat state.

The course materials are private to preserve the assignment for future offerings. If you would like to know more, feel free to reach out.
