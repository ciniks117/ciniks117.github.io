---
layout: post
title: Direction of Gradient
date: 2015-05-04 11:59:00-0400
description: Gradient is the direction of steepest asccent
comments: true
categories: ['Machine Learning']
---

### Gradient is the direction of steepest asccent

#### Gradient
The gradient of a vector valued differentiable function $$\nabla f: R^n \rightarrow R^n$$  at a point $$p$$, is a vector whose components are the partial derivative of $$f$$:

$$\begin{equation}
\nabla f(p) = \begin{bmatrix}
\frac{\delta f(p)}{\delta x_1} \\
... \\
\frac{\delta f(p)}{\delta x_n}
\end{bmatrix}
\end{equation}
    $$

Let's thinks of a function $$f(x,y) = x^2y^2$$. We can think of partial derivative of this function as the value of $$f$$ while:
- Treating $$x$$ as constant and nudge $$y$$ a little bit
- Treating $$y$$ as constant and nudge $$x$$ a little bit

We infer that we nudge the inputs to $$f$$ in the direction of two perpendicular unit vectors along the $$x,y$$ axis. Now suppose we want to nudge the function along some vector $$\vec{v}$$.

This function can be reprsented by 3D graph where $$x$$, $$y$$ represent the inputs to the function and $$z$$ represents the output. The partial derivative of this function is a vector