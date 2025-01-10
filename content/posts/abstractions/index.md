+++
date  = "2025-01-08T17:48:22+05:30"
title = 'Abstractions - From Nature to AI'

tags = [
    "nature to electronics",
]

categories = [
    "basics",
]

series = ["basics"]
images = ["c.svg"]

draft=true
+++

The layers of abstraction all the way down to Nature that lead us to the world of Electronics, Solid State machines and AI. This article explores the contracts that got us to where we are.Let us start by asking the question -

<!--more-->

> `Why did humans care to investigate and understand nature?`

While the answer to this can vary depending on who is answering it, I think we can safely latch on to reasons based on survival. Being able to predict rains would have helped seek shelter in time, being able to make tools certainly helped hunt more reliably and the discovery of **fire** catapulted us on the top of the food chain. Life in general is a suffering and operating in alignment with the laws of nature seemed like a way to provide a way to use her natural course of actions to skip the additional pain, example - falling from a tree kills or disables, so don't jump off of a tall tree.

## Tables

As I mentioned earlier, we don't necessarily know all the laws of Nature. It's a constant pursuit to measure changes[^1] by running experiments. And as we perform experiments, we make **tables** tracking the changes in one parameter by varying another. Usually, we start by tabulating the data. That is what the early day scientists and explorer did - **Kepler** tabulated the positions of the planets and **Ohm** did the same with Voltage and current.

He discovered the linear relation between the two. And the relation stays linear as long as other physical quantities like temperature and pressure remain constant. That is the contract!

And again, we can use the equation as long as the contract or preconditions are met (the temperature and pressure being constant). The moment we break the contract we can no longer expect the equation to give us the right predictions and we must go back to measuring and making tables mapping the relation between the quantities in different conditions...

## Maxwell's Equations

As we experimented more and more, we discovered Laws of Nature that we represent using equations. The Ohm's Law for example is $V=IR$. We no longer have to maintain tables, we can predict the future/behavior by relying on equations.

Studying nature to look for Laws is `Physics`. Studying the behavior of charges is captured within the specialization of Electromagnetism. And `Maxwell's Equations` (as listed below) sum all of it.

$$\nabla \cdot \mathbf{E} = \frac{\rho}{\epsilon_0} \quad$$
$$\nabla \cdot \mathbf{B} = 0 \quad$$
$$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t} \quad$$
$$\nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t} \quad$$

These equations give us the general behavior of charges and the effect of Electric and Magnetic field. We can predicting everything about the electrical and magnetic behavior using these equations.

## Lumped Matter Abstraction

Solving **Maxwell's Equations** for every electrical/magnetic configuration/setup is tedious. One can of course use these to solve it but what folks observed over time is, if certain boundary conditions are met, the equations boil down to being simple equations.

## Amplifiers

## Digital Abstraction

## Combinational Logic

## Clocked Abstraction

## Instruction Set Architecture

## Language Abstractions

## System Calls and OS

## API

## Applications

[^1]: We always only measure the difference or change.
