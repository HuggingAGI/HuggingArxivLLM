# # 探索从工具调用到符号思维：LLMs在持续Lisp元编程循环中的应用

发布时间：2025年06月08日

`LLM应用` `人工智能`

> From Tool Calling to Symbolic Thinking: LLMs in a Persistent Lisp Metaprogramming Loop

# 摘要

> 我们提出了一种创新架构，将大型语言模型（LLMs）与持久的交互式Lisp环境相结合。通过与实时REPL的程序交互，LLMs能够定义、调用和进化自己的工具。系统通过在生成过程中嵌入Lisp表达式，并借助中间件层进行拦截，实现了有状态的外部记忆、反射式编程和动态工具创建。我们还提出了一套设计框架和架构原则，为未来实现符号编程与神经语言生成相结合的交互式AI系统提供了指导。

> We propose a novel architecture for integrating large language models (LLMs) with a persistent, interactive Lisp environment. This setup enables LLMs to define, invoke, and evolve their own tools through programmatic interaction with a live REPL. By embedding Lisp expressions within generation and intercepting them via a middleware layer, the system allows for stateful external memory, reflective programming, and dynamic tool creation. We present a design framework and architectural principles to guide future implementations of interactive AI systems that integrate symbolic programming with neural language generation.

[Arxiv](https://arxiv.org/abs/2506.10021)