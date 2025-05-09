# **GroverGPT-2：借助链式推理与量子原生分词模拟Grover算法**

发布时间：2025年05月07日

`LLM应用

摘要中提到使用大型语言模型（LLMs）来模拟量子算法，特别是Grover算法，并探讨了其在量子计算模拟中的应用。这属于将LLMs应用于特定领域，因此归类为LLM应用。` `量子计算` `人工智能`

> GroverGPT-2: Simulating Grover's Algorithm via Chain-of-Thought Reasoning and Quantum-Native Tokenization

# 摘要

> 量子计算在特定任务上展现出超越经典计算的理论优势，但实用量子优势的实际边界仍是未解之谜。为了揭开这一谜题，我们需要探究经典机器是否具备学习与模拟量子算法的能力。近期大型语言模型（LLMs）展现出的强大推理能力，激发了我们探索其在这一领域潜力的兴趣。在本研究中，我们推出了GroverGPT-2——一种基于LLMs、结合Chain-of-Thought（CoT）推理与量子原生分词的Grover算法模拟方法。相较于前作，GroverGPT-2能够直接从量子电路表示进行模拟，并生成结构清晰、易于理解的输出。实验结果表明，通过高效处理量子原生分词，GroverGPT-2成功掌握了量子电路逻辑，这有力证明了经典模型如LLMs能够捕捉量子算法的内在结构。此外，GroverGPT-2的独特之处在于它将电路数据与自然语言相结合，将推理过程自然融入模拟之中。这种双重能力使其成为推进机器理解量子算法及建模量子电路逻辑的原型工具。我们还发现GroverGPT-2的扩展规律，随着量子比特数量增加，这一发现为实现可扩展的经典模拟提供了新思路。这些突破不仅为探索经典模拟的极限开辟了新方向，也为提升量子教育与研究水平奠定了基础，并为未来量子计算领域的基础模型研究铺平了道路。

> Quantum computing offers theoretical advantages over classical computing for specific tasks, yet the boundary of practical quantum advantage remains an open question. To investigate this boundary, it is crucial to understand whether, and how, classical machines can learn and simulate quantum algorithms. Recent progress in large language models (LLMs) has demonstrated strong reasoning abilities, prompting exploration into their potential for this challenge. In this work, we introduce GroverGPT-2, an LLM-based method for simulating Grover's algorithm using Chain-of-Thought (CoT) reasoning and quantum-native tokenization. Building on its predecessor, GroverGPT-2 performs simulation directly from quantum circuit representations while producing logically structured and interpretable outputs. Our results show that GroverGPT-2 can learn and internalize quantum circuit logic through efficient processing of quantum-native tokens, providing direct evidence that classical models like LLMs can capture the structure of quantum algorithms. Furthermore, GroverGPT-2 outputs interleave circuit data with natural language, embedding explicit reasoning into the simulation. This dual capability positions GroverGPT-2 as a prototype for advancing machine understanding of quantum algorithms and modeling quantum circuit logic. We also identify an empirical scaling law for GroverGPT-2 with increasing qubit numbers, suggesting a path toward scalable classical simulation. These findings open new directions for exploring the limits of classical simulatability, enhancing quantum education and research, and laying groundwork for future foundation models in quantum computing.

[Arxiv](https://arxiv.org/abs/2505.04880)