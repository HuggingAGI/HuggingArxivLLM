# 联想记忆为使用新颖的注意力残差流架构改进上下文学习带来了启发。

发布时间：2024年12月19日

`LLM理论` `计算机科学` `神经科学`

> Associative memory inspires improvements for in-context learning using a novel attention residual stream architecture

# 摘要

> 大型语言模型（LLMs）展现出非凡的能力，能利用输入序列中的信息，对训练期间未曾见过的数据做出恰当回应，此能力被称作上下文学习（ICL）。人类和非人类动物也有类似能力，但其神经架构与LLMs差异显著。不过，LLMs中的关键组件——注意力机制，与现代联想记忆模型相似，该模型在计算神经科学界被广泛用于模拟生物记忆系统并受其影响。基于此关联，我们引入了一个能够进行ICL的联想记忆模型，并受其启发设计了一种新的残差流架构，使信息能在注意力头之间直接流动。我们在两层Transformer的训练中测试了该架构，发现其ICL能力比未修改时更快显现。随后，我们将该架构应用于拥有800万参数的小型语言模型，重点关注注意力头的值，结果显示在更大且更自然的规模下，ICL性能有所提升。

> Large language models (LLMs) demonstrate an impressive ability to utilise information within the context of their input sequences to appropriately respond to data unseen by the LLM during its training procedure. This ability is known as in-context learning (ICL). Humans and non-human animals demonstrate similar abilities, however their neural architectures differ substantially from LLMs. Despite this, a critical component within LLMs, the attention mechanism, resembles modern associative memory models, widely used in and influenced by the computational neuroscience community to model biological memory systems. Using this connection, we introduce an associative memory model capable of performing ICL. We use this as inspiration for a novel residual stream architecture which allows information to directly flow between attention heads. We test this architecture during training within a two-layer Transformer and show its ICL abilities manifest more quickly than without this modification. We then apply our architecture in small language models with 8 million parameters, focusing on attention head values, with results also indicating improved ICL performance at this larger and more naturalistic scale.

[Arxiv](https://arxiv.org/abs/2412.15113)