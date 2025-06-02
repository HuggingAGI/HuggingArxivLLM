# Period-LLM：增强多模态大型语言模型的周期性能力

发布时间：2025年05月30日

`LLM应用` `自然过程` `多模态模型`

> Period-LLM: Extending the Periodic Capability of Multimodal Large Language Model

# 摘要

> 周期性或拟周期性现象在天气模式、运动行为、交通流和生物信号等自然过程中展现了其独特的内在特征。由于这些现象跨越多种模态，多模态大型语言模型（MLLMs）在捕捉和理解其复杂性方面展现出巨大潜力。然而，现有的MLLMs在处理周期性任务时面临两大挑战：一是缺乏时间建模能力，二是短期与长期周期之间的冲突。本文提出了Period-LLM，这是一种专为增强多模态周期性任务性能设计的多模态大型语言模型，并构建了一个难度各异的基准测试，用于评估大型模型的跨模态周期能力。特别地，我们采用了一种“从简单到复杂”的泛化范式，从相对简单的文本任务开始，逐步过渡到更复杂的视觉和多模态任务，确保模型能够逐步建立起强大的周期性推理能力。此外，我们提出了“抵制逻辑遗忘”的优化策略，以在语义对齐过程中保持周期性推理能力。大量实验表明，所提出的Period-LLM在周期性任务中优于现有的MLLMs。代码可在https://github.com/keke-nice/Period-LLM获取。

> Periodic or quasi-periodic phenomena reveal intrinsic characteristics in various natural processes, such as weather patterns, movement behaviors, traffic flows, and biological signals. Given that these phenomena span multiple modalities, the capabilities of Multimodal Large Language Models (MLLMs) offer promising potential to effectively capture and understand their complex nature. However, current MLLMs struggle with periodic tasks due to limitations in: 1) lack of temporal modelling and 2) conflict between short and long periods. This paper introduces Period-LLM, a multimodal large language model designed to enhance the performance of periodic tasks across various modalities, and constructs a benchmark of various difficulty for evaluating the cross-modal periodic capabilities of large models. Specially, We adopt an "Easy to Hard Generalization" paradigm, starting with relatively simple text-based tasks and progressing to more complex visual and multimodal tasks, ensuring that the model gradually builds robust periodic reasoning capabilities. Additionally, we propose a "Resisting Logical Oblivion" optimization strategy to maintain periodic reasoning abilities during semantic alignment. Extensive experiments demonstrate the superiority of the proposed Period-LLM over existing MLLMs in periodic tasks. The code is available at https://github.com/keke-nice/Period-LLM.

[Arxiv](https://arxiv.org/abs/2505.24476)