---
layout: blog
title: Notes on Lagrangian Mechanics
date: 2021-04-18T01:31:14-07:00
draft: false
---
These are notes based on Mechanics by Landau and Lifshitz. Going over the main points in each chapter and derivations which needed more detail

# Principle of Least Action

* Generalized Coordinates : Any $s$ quantities $$ q_1, q_2, ..., q_3 $$ which define the position of a system with $$ s $$ degrees of freedom.
* Generalized Velocities : The respective time derivatives $$\dot{q}_1, \dot{q}_2, ..., \dot{q}_3$$ of the generalized coordinates

If at an instant all generalized coordinates $$q$$ and generalized velocities $$\dot{q}$$ are given, the accelerations $$\ddot{q}$$ at that instant are uniquely defined.

Mechanical motion is characterized by a function $$L(q,\dot{q},t)$$ and a condition where at instants $$t_1, t_2$$ in time the positions $$q_1, q_2$$ change such that the integral
$$
S = \int^{t_2}_{t_1} L(q,\dot{q},t) dt
$$
takes an extremum value. 