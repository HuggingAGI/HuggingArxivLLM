# 噪声对大型语言模型（LLMs）在抽象与推理语料库（ARC）任务中性能的显著影响——基于模型温度的分析

发布时间：2025年04月22日

`LLM理论` `人工智能` `模型推理`

> Impact of Noise on LLM-Models Performance in Abstraction and Reasoning Corpus (ARC) Tasks with Model Temperature Considerations

# 摘要

> 大型语言模型（LLMs）在结构化推理能力方面取得了显著进展，尤其是在抽象和模式识别任务中表现突出。抽象与推理语料库（ARC）基准测试是评估这些能力的关键工具，它检验AI模型在面对新问题时的泛化能力。GPT-4o在零噪声条件下成功解决了所有ARC任务，展现出强大的性能，而DeepSeek R1和LLaMA 3.2等其他模型则未能解决任何任务，这表明它们在推理能力上存在局限性，难以超越简单的模式匹配。为了探究这一差距，我们系统性地评估了这些模型在不同噪声水平和温度设置下的表现。研究发现，无论模型架构如何，噪声的引入都会一致地削弱模型性能。这一趋势揭示了一个共同的脆弱性：尽管当前的LLMs显示出抽象推理的迹象，但它们仍然对输入的微小扰动高度敏感。这种脆弱性引发了对其在现实世界中应用能力的担忧，因为噪声和不确定性在现实场景中普遍存在。通过比较不同模型架构对这些挑战的响应，我们揭示了现代LLMs在推理任务中的结构性弱点。这项研究强调了开发更加稳健和适应性强的AI系统的重要性，这些系统需要能够应对现实场景中固有的模糊性和变化性。我们的研究发现旨在为未来的研究提供指导，推动模型在泛化能力、稳健性和与人类认知灵活性的对齐方面取得进展。

> Recent advancements in Large Language Models (LLMs) have generated growing interest in their structured reasoning capabilities, particularly in tasks involving abstraction and pattern recognition. The Abstraction and Reasoning Corpus (ARC) benchmark plays a crucial role in evaluating these capabilities by testing how well AI models generalize to novel problems. While GPT-4o demonstrates strong performance by solving all ARC tasks under zero-noise conditions, other models like DeepSeek R1 and LLaMA 3.2 fail to solve any, suggesting limitations in their ability to reason beyond simple pattern matching. To explore this gap, we systematically evaluate these models across different noise levels and temperature settings. Our results reveal that the introduction of noise consistently impairs model performance, regardless of architecture. This decline highlights a shared vulnerability: current LLMs, despite showing signs of abstract reasoning, remain highly sensitive to input perturbations. Such fragility raises concerns about their real-world applicability, where noise and uncertainty are common. By comparing how different model architectures respond to these challenges, we offer insights into the structural weaknesses of modern LLMs in reasoning tasks. This work underscores the need for developing more robust and adaptable AI systems capable of handling the ambiguity and variability inherent in real-world scenarios. Our findings aim to guide future research toward enhancing model generalization, robustness, and alignment with human-like cognitive flexibility.

[Arxiv](https://arxiv.org/abs/2504.15903)