---
layout: page
title: ENN Snake Game — Neural Network Trained with Genetic Algorithm
description: Training neural networks to play Snake autonomously using evolutionary algorithms — implemented in JavaScript
img: assets/img/projects/enn_snake_game/enn_snake_game.jpg
importance: 1
category: software
toc:
  sidebar: left
---

> ##### PROJECT HIGHLIGHTS
>
> **Genetic Algorithm** evolution • **Parallel training** across multiple agents • **Autonomous gameplay** with no human input
>
> 📅 May 2019 – Jun 2019 | 💻 JavaScript | 🧬 Evolutionary Neural Network
{: .block-tip }

## Project Overview
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

**Type:** Personal Project<br>
**Period:** May 2019 – Jun 2019<br>
**Language:** JavaScript / HTML<br>
**Repository:** [github.com/vuluanhtu/ENN-Snake-Game](https://github.com/vuluanhtu/ENN-Snake-Game)

Developed a system that trains neural networks to play the classic Snake game entirely on their own — with no hard-coded rules or human guidance. The networks learn through **evolution**: each generation, the best-performing agents are selected, their "genes" (network weights) are mutated and recombined, and a new generation is bred. Over hundreds of generations, increasingly capable snakes emerge.

[View Source Code on GitHub](https://github.com/vuluanhtu/ENN-Snake-Game){: .btn .btn-sm .z-depth-1}

---

## How It Works
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

### Neural Network Architecture
{: .mt-4 .mb-3 .font-weight-bold }

Each snake is controlled by a neural network that takes the game state as input and outputs a movement direction. The network processes information about:

- Distance to walls in each direction
- Distance to the food target
- Direction of the snake's current movement
- Proximity of the snake's own body

The network outputs are mapped to the four movement directions — up, down, left, right — and the snake acts on the highest-confidence output each frame.

### Genetic Algorithm — Evolutionary Training
{: .mt-4 .mb-3 .font-weight-bold }

Rather than using traditional backpropagation (which requires labeled training data), this project uses a **genetic algorithm** — a biologically-inspired optimization method:

1. **Initialization** — A population of snakes with random network weights is created
2. **Evaluation** — Each snake plays the game until it dies; its score is used as a fitness measure
3. **Selection** — The highest-scoring snakes are kept as "parents" for the next generation
4. **Crossover** — Parent networks are combined to create offspring networks, mixing their weights
5. **Mutation** — Small random changes are applied to offspring weights, introducing variation
6. **Repeat** — The new generation plays and the cycle continues

Over hundreds of generations, this process naturally evolves snakes that score higher and higher — all without any manually written gameplay logic.

---

## Training Process
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

To speed up evolution, multiple neural networks are trained **simultaneously**, each in their own independent game environment. This parallel approach allows many agents to be evaluated at once per generation, dramatically accelerating the evolutionary search.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/projects/enn_snake_game/2026-02-19 20-10-56.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
  </div>
</div>
<div class="caption">
  Training process: multiple neural networks playing Snake simultaneously in parallel, each evolving independently
</div>

---

## Train Result
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

After sufficient generations, the evolved neural network demonstrates competent autonomous Snake gameplay — navigating toward food, avoiding walls, and managing its own growing body with no human input.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/projects/enn_snake_game/2026-02-19 20-01-51.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true muted=true %}
  </div>
</div>
<div class="caption">
  Train result: a fully trained neural network playing Snake autonomously after hundreds of generations of evolution
</div>

---

## Play It Yourself
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

The trained neural network runs live in your browser — click **Initialize** to watch the AI play:

<div class="row justify-content-sm-center">
  <div class="col-sm-auto mt-3 mt-md-0">
    <iframe
      src="{{ '/assets/html/enn_snake_game/index.html' | relative_url }}"
      width="420"
      height="460"
      style="border: 1px solid #ccc; border-radius: 4px;"
      title="ENN Snake Game"
    ></iframe>
  </div>
</div>
<div class="caption">
  Live demo: click Initialize to start — the AI plays Snake autonomously using the trained neural network
</div>

---

## Technical Skills Demonstrated
{: .mt-5 .mb-4 .border-bottom .pb-3 .font-weight-bold }

- **Neural Networks** — Design and implementation of feedforward networks from scratch
- **Genetic Algorithms** — Evolutionary optimization: selection, crossover, and mutation
- **JavaScript / HTML** — Full browser-based implementation with real-time rendering
- **Parallel Simulation** — Running multiple independent agent environments simultaneously
- **AI & Machine Learning** — Reinforcement learning concepts applied without labeled data
- **Algorithm Design** — Custom implementation of evolutionary training loop
