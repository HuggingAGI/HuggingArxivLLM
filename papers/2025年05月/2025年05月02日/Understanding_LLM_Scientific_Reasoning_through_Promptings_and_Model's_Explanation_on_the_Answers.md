# 通过提示与模型解释，解析 LLM 的科学推理能力。

发布时间：2025年05月02日

`LLM理论` `科学推理` `复杂推理`

> Understanding LLM Scientific Reasoning through Promptings and Model's Explanation on the Answers

# 摘要

> # 摘要
大型语言模型（LLMs）在自然语言理解、推理和问题解决方面展现出了卓越的能力，但其在复杂多步骤推理任务中的表现仍有待提升，这对科学、医学和法律等领域至关重要。本文深入探讨了当代LLMs的推理能力，分析了它们的优缺点及改进潜力。

研究采用提示工程方法，在研究生级别的GoogleProof问答（GPQA）数据集上评估了GPT-4o的科学推理能力。测试了五种流行的提示工程技术和两种定制提示：基线直接回答（零样本）、思维链（CoT）、零样本CoT、自我提问、自我一致性、分解和多路径提示。

研究发现，尽管LLMs表现出新兴的推理能力，但它们往往依赖于模式识别，而非真正的逻辑推理，这导致在复杂问题解决中出现不一致。结果显示，自我一致性在所有提示工程技术中表现最佳，准确率为52.99%，紧随其后的是直接回答（52.23%）。零样本CoT（50%）的表现优于多路径（48.44%）、分解（47.77%）、自我提问（46.88%）和CoT（43.75%）。在解释答案方面，自我一致性表现第二差。

简单技术如直接回答、CoT和零样本CoT在科学推理方面表现最佳。我们提出了一项研究议程，旨在通过整合结构化推理框架、混合AI方法和人类在环方法来弥合这些差距。通过批判性地评估LLMs的推理机制，本文为通用人工智能的未来以及更强大、更值得信赖的AI系统的开发做出了贡献。

> Large language models (LLMs) have demonstrated remarkable capabilities in natural language understanding, reasoning, and problem-solving across various domains. However, their ability to perform complex, multi-step reasoning task-essential for applications in science, medicine, and law-remains an area of active investigation. This paper examines the reasoning capabilities of contemporary LLMs, analyzing their strengths, limitations, and potential for improvement. The study uses prompt engineering techniques on the Graduate-Level GoogleProof Q&A (GPQA) dataset to assess the scientific reasoning of GPT-4o. Five popular prompt engineering techniques and two tailored promptings were tested: baseline direct answer (zero-shot), chain-of-thought (CoT), zero-shot CoT, self-ask, self-consistency, decomposition, and multipath promptings. Our findings indicate that while LLMs exhibit emergent reasoning abilities, they often rely on pattern recognition rather than true logical inference, leading to inconsistencies in complex problem-solving. The results indicated that self-consistency outperformed the other prompt engineering technique with an accuracy of 52.99%, followed by direct answer (52.23%). Zero-shot CoT (50%) outperformed multipath (48.44%), decomposition (47.77%), self-ask (46.88%), and CoT (43.75%). Self-consistency performed the second worst in explaining the answers. Simple techniques such as direct answer, CoT, and zero-shot CoT have the best scientific reasoning. We propose a research agenda aimed at bridging these gaps by integrating structured reasoning frameworks, hybrid AI approaches, and human-in-the-loop methodologies. By critically evaluating the reasoning mechanisms of LLMs, this paper contributes to the ongoing discourse on the future of artificial general intelligence and the development of more robust, trustworthy AI systems.

[Arxiv](https://arxiv.org/abs/2505.01482)