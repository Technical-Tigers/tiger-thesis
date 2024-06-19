# Measuring and improving resource utilization in a Kubernetes cluster serving AI inference tasks

Recent developments in large language models (LLMs) have popularized the usage
of AI apps among the general public and have increased the strain on the limited
resources available. These large models are often run on distributed systems
composed of multiple physical machines and managed by the Kubernetes platform.
In this thesis, we evaluate the current strategies available for scheduling AI
inference tasks in Kubernetes clusters and try to optimize them based on recent
work in the field. To achieve our goal of utilizing the available resources to
their full extent, we look for an algorithm well suited for this scenario. To
test our solutions, we provide an environment for simulating various scheduling
strategies and analyzing how they behave under different circumstances.

## About

This is a Bachelor's Thesis written in 2024 by Piotr Blinowski, Szymon Mrozicki,
Szymon Potrzebowski and Karol Wąsowski, under the supervision of Janina
Daszkiewicz-Mincel at the University of Warsaw's Faculty of Mathematics,
Computer Science and Mechanics.

If you're looking for the simulator that we built as part of the project,
please see [here](https://github.com/technical-tigers/tiger-simulator).

