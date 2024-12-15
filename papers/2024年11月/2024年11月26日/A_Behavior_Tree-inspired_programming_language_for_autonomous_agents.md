# 一种为自主代理而设计的、受行为树启发的编程语言

发布时间：2024年11月26日

`Agent` `机器人` `人工智能`

> A Behavior Tree-inspired programming language for autonomous agents

# 摘要

> 我们基于行为树（BTs）的理念和动机，为自主代理设计了一种函数式编程语言。BTs 是机器人和人工智能领域中用于设计代理行为的常用模型。然而，随着其迅速发展，BTs 的简单模型渐显局限。人们越来越多地推动增强 BTs 的功能，最终期望 BTs 能自身演变成一种编程语言，以模块化和反应性等 BT 特性为核心。
在本文中，我们探讨了 BT 模型要如何扩展才能成为这样一种语言。我们明确了一些必须解决的基本问题：实现“反应式”选择、“监控”安全关键条件以及动作间的数据传递。我们给出了多个小示例，表明这些问题颇为复杂，当前的 BT 方法在处理时不符合模块化原则。相反，我们提供了一组简单的模块化编程基本元素来处理这些用例，并展示了如何将它们组合以构建复杂程序。我们给出了受 BT 启发的语言的完整规范，并在函数式编程语言 Haskell 中给出了实现。最后，我们通过将一个大型复杂的 BT 转化为简单清晰的程序来展示我们的语言。

> We propose a design for a functional programming language for autonomous agents, built off the ideas and motivations of Behavior Trees (BTs). BTs are a popular model for designing agents behavior in robotics and AI. However, as their growth has increased dramatically, the simple model of BTs has come to be limiting. There is a growing push to increase the functionality of BTs, with the end goal of BTs evolving into a programming language in their own right, centred around the defining BT properties of modularity and reactiveness.
  In this paper, we examine how the BT model must be extended in order to grow into such a language. We identify some fundamental problems which must be solved: implementing `reactive' selection, 'monitoring' safety-critical conditions, and passing data between actions. We provide a variety of small examples which demonstrate that these problems are complex, and that current BT approaches do not handle them in a manner consistent with modularity. We instead provide a simple set of modular programming primitives for handling these use cases, and show how they can be combined to build complex programs. We present a full specification for our BT-inspired language, and give an implementation in the functional programming language Haskell. Finally, we demonstrate our language by translating a large and complex BT into a simple, unambiguous program.

[Arxiv](https://arxiv.org/abs/2412.08654)