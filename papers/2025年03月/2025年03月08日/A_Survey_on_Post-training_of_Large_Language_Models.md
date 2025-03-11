# # 大型语言模型后训练研究综述
本文综述了大型语言模型（LLMs）后训练的相关研究。

发布时间：2025年03月08日

`LLM理论

摘要讨论了大型语言模型（LLMs）的局限性以及后训练语言模型（PoLMs）的发展，详细分析了这些模型的演变和核心技术，属于对模型本身的理论探讨和改进，因此归类为LLM理论。` `人工智能` `科学研究`

> A Survey on Post-training of Large Language Models

# 摘要

> 大型语言模型（LLMs）的问世彻底改变了自然语言处理领域，使其在从对话系统到科学探索的各个领域中发挥着不可或缺的作用。然而，在特定应用背景下，这些预训练架构往往暴露出一些局限性，包括受限的推理能力、伦理上的不确定性以及在特定领域表现不佳等问题。为了解决这些不足，先进的后训练语言模型（PoLMs）应运而生，例如 OpenAI-o1/o3 和 DeepSeek-R1（统称为大型推理模型，或 LRMs）。本文首次对后训练语言模型（PoLMs）进行了全面综述，系统性地梳理了它们在五个核心范式中的演变历程：微调，以提升任务特定的准确性；对齐，以确保与人类偏好保持一致；推理，以增强多步推理能力，尽管奖励设计面临挑战；效率，以在日益复杂的情况下优化资源利用；以及整合与适应，以扩展跨不同模态的能力，同时解决连贯性问题。从 ChatGPT 的基础对齐策略到 DeepSeek-R1 的创新推理进步，我们展示了 PoLMs 如何利用数据集来缓解偏见、深化推理能力并提升领域适应性。我们的贡献包括首次对 PoLM 进化进行的开创性综合分析、一套结构化的分类法用于分类技术与数据集，以及一项战略议程，强调 LRMs 在提高推理熟练度和领域灵活性方面的作用。作为同类研究中首个全面覆盖该领域的综述，本研究整合了近期 PoLM 的进展，并为未来研究奠定了严谨的智力框架，推动了 LLMs 的发展，使其在科学和社会应用中具备更高的精确性、伦理稳健性和灵活性。

> The emergence of Large Language Models (LLMs) has fundamentally transformed natural language processing, making them indispensable across domains ranging from conversational systems to scientific exploration. However, their pre-trained architectures often reveal limitations in specialized contexts, including restricted reasoning capacities, ethical uncertainties, and suboptimal domain-specific performance. These challenges necessitate advanced post-training language models (PoLMs) to address these shortcomings, such as OpenAI-o1/o3 and DeepSeek-R1 (collectively known as Large Reasoning Models, or LRMs). This paper presents the first comprehensive survey of PoLMs, systematically tracing their evolution across five core paradigms: Fine-tuning, which enhances task-specific accuracy; Alignment, which ensures alignment with human preferences; Reasoning, which advances multi-step inference despite challenges in reward design; Efficiency, which optimizes resource utilization amidst increasing complexity; and Integration and Adaptation, which extend capabilities across diverse modalities while addressing coherence issues. Charting progress from ChatGPT's foundational alignment strategies to DeepSeek-R1's innovative reasoning advancements, we illustrate how PoLMs leverage datasets to mitigate biases, deepen reasoning capabilities, and enhance domain adaptability. Our contributions include a pioneering synthesis of PoLM evolution, a structured taxonomy categorizing techniques and datasets, and a strategic agenda emphasizing the role of LRMs in improving reasoning proficiency and domain flexibility. As the first survey of its scope, this work consolidates recent PoLM advancements and establishes a rigorous intellectual framework for future research, fostering the development of LLMs that excel in precision, ethical robustness, and versatility across scientific and societal applications.

[Arxiv](https://arxiv.org/abs/2503.06072)