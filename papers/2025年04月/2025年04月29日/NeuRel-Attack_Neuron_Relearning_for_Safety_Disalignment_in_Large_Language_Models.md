# NeuRel-Attack：针对大型语言模型安全性错位的神经重学攻击方法

发布时间：2025年04月29日

`LLM理论

理由：这篇论文深入探讨了大型语言模型内部的安全对齐机制，分析了神经元在安全约束中的作用，并提出了通过修改神经元来影响模型行为的方法。这属于对模型内在机制的理论研究，因此归类为LLM理论。` `人工智能`

> NeuRel-Attack: Neuron Relearning for Safety Disalignment in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的安全对齐通过微调机制实现，这些机制通过调节神经元激活来抑制有害内容的生成。本研究提出了一种 novel 方法，通过识别并修改负责安全约束的神经元来诱导对齐失效。我们的方法包含三个关键步骤：首先，通过神经元激活分析，我们检查模型对有害和无害提示的激活模式，以识别在区分有害和无害输入中起关键作用的神经元；其次，基于相似性的神经元识别系统地定位负责安全对齐的神经元；最后，在安全移除的神经元再学习步骤中，我们对选定的神经元进行微调，以恢复模型生成之前受限响应的能力。实验结果表明，我们的方法在仅进行少量微调的情况下，能够有效移除安全约束，凸显了当前对齐技术中一个关键的脆弱性。我们的发现强调了在大型语言模型中建立强大的防御机制以抵御对抗性微调攻击的迫切需求。

> Safety alignment in large language models (LLMs) is achieved through fine-tuning mechanisms that regulate neuron activations to suppress harmful content. In this work, we propose a novel approach to induce disalignment by identifying and modifying the neurons responsible for safety constraints. Our method consists of three key steps: Neuron Activation Analysis, where we examine activation patterns in response to harmful and harmless prompts to detect neurons that are critical for distinguishing between harmful and harmless inputs; Similarity-Based Neuron Identification, which systematically locates the neurons responsible for safe alignment; and Neuron Relearning for Safety Removal, where we fine-tune these selected neurons to restore the model's ability to generate previously restricted responses. Experimental results demonstrate that our method effectively removes safety constraints with minimal fine-tuning, highlighting a critical vulnerability in current alignment techniques. Our findings underscore the need for robust defenses against adversarial fine-tuning attacks on LLMs.

[Arxiv](https://arxiv.org/abs/2504.21053)