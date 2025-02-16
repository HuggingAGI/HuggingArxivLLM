# GroverGPT: 80亿参数量的大型语言模型，专为量子搜索设计

发布时间：2025年02月11日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在模拟量子图灵机输出中的应用，特别是基于格罗弗量子电路。研究者开发了一个特定的模型（GroverGPT）用于模拟量子搜索算法，展示了其在量子计算模拟中的有效性。这属于将LLMs应用于特定任务的研究，因此归类为LLM应用。` `量子计算` `量子信息科学`

> GroverGPT: A Large Language Model with 8 Billion Parameters for Quantum Searching

# 摘要

> 量子计算作为非冯·诺伊曼范式，为特定问题带来了超越经典计算的可证明加速。然而，在当前嘈杂量子设备环境下，量子电路的经典模拟能力仍存在诸多未解之谜。本研究聚焦于利用大型语言模型（LLMs）模拟量子图灵机的输出，特别是基于格罗弗量子电路，该电路以相较于经典算法的二次加速著称。为此，我们开发了基于LLaMA架构的GroverGPT模型，经过15万亿令牌的训练。与需要大量计算资源的暴力状态向量模拟不同，GroverGPT通过模式识别近似量子搜索算法，无需显式量子态表示。在97,000个量子搜索实例的分析中，GroverGPT的表现超越了OpenAI的GPT-4o（45%准确率），在6-和10-量子比特数据集上，准确率接近100%（基于4量子比特或更大训练集）。其强大的泛化能力在基于3至6量子比特数据训练时，对超过20量子比特系统的准确率超过95%。分析表明，GroverGPT捕捉到了格罗弗搜索的量子特性，而非经典模式，这一结论得到了新型提示策略的支持，从而提升了性能表现。尽管系统规模增大导致准确率下降，但这些发现为我们理解经典模拟的实际边界提供了重要见解。这项工作表明，针对特定任务的LLMs在量子算法学习方面能够超越通用模型如GPT-4o，并可作为推进量子研究的有力工具。

> Quantum computing is an exciting non-Von Neumann paradigm, offering provable speedups over classical computing for specific problems. However, the practical limits of classical simulatability for quantum circuits remain unclear, especially with current noisy quantum devices. In this work, we explore the potential of leveraging Large Language Models (LLMs) to simulate the output of a quantum Turing machine using Grover's quantum circuits, known to provide quadratic speedups over classical counterparts. To this end, we developed GroverGPT, a specialized model based on LLaMA's 8-billion-parameter architecture, trained on over 15 trillion tokens. Unlike brute-force state-vector simulations, which demand substantial computational resources, GroverGPT employs pattern recognition to approximate quantum search algorithms without explicitly representing quantum states. Analyzing 97K quantum search instances, GroverGPT consistently outperformed OpenAI's GPT-4o (45\% accuracy), achieving nearly 100\% accuracy on 6- and 10-qubit datasets when trained on 4-qubit or larger datasets. It also demonstrated strong generalization, surpassing 95\% accuracy for systems with over 20 qubits when trained on 3- to 6-qubit data. Analysis indicates GroverGPT captures quantum features of Grover's search rather than classical patterns, supported by novel prompting strategies to enhance performance. Although accuracy declines with increasing system size, these findings offer insights into the practical boundaries of classical simulatability. This work suggests task-specific LLMs can surpass general-purpose models like GPT-4o in quantum algorithm learning and serve as powerful tools for advancing quantum research.

[Arxiv](https://arxiv.org/abs/2501.00135)