---
layout: page
title: micrograd
description: A scalar autograd engine and tiny neural-net library, built from scratch
img:
importance: 3
category: projects
github: https://github.com/frankhou42/micrograd
---

**micrograd** is a tiny automatic-differentiation engine and neural-network library built from
scratch — no PyTorch, no autograd black box — to make the mechanics of backpropagation concrete.

**Stack:** Python.

**Highlights**

- A `Value` type that records operations into a computation graph.
- Reverse-mode autodiff: `.backward()` walks the graph in topological order and accumulates gradients
  via the chain rule.
- A small MLP trained with gradient descent, plus Graphviz visualization of the graph.

[View on GitHub →](https://github.com/frankhou42/micrograd)
