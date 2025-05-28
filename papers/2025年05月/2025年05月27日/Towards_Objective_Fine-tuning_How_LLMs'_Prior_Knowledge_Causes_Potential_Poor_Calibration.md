# # 目标导向的微调：LLMs的先验知识如何可能导致潜在的校准偏差？

发布时间：2025年05月27日

`LLM理论

摘要讨论了微调后的大型语言模型的校准问题，分析了先验知识对模型性能的影响，并提出了新的框架来改进校准。这些内容属于模型的内在机制和理论研究，因此归类为LLM理论。` `人工智能交互` `人工智能`

> Towards Objective Fine-tuning: How LLMs' Prior Knowledge Causes Potential Poor Calibration?

# 摘要

> 微调后的大型语言模型（LLMs）常表现出较差的校准，置信度与实际性能不一致。尽管校准在从头训练的模型中得到广泛研究，但LLMs在微调过程中先验知识对校准的影响仍研究不足。我们的研究表明，LLMs的先验知识由于在现实世界的微调中普遍存在已知数据，可能会导致潜在的不良校准。具体来说，与LLMs先验知识一致的数据会导致过度自信，而新知识则会改善校准。这揭示了一种矛盾：百科全书式的知识使任务多样化，但通过不可避免的知识重叠削弱了校准。为此，我们提出了CogCalib，一种认知感知框架，根据模型的先验知识应用有针对性的学习策略。使用3个LLM家族在7个任务上的实验表明，CogCalib显著提高了校准，同时保持了性能，在Llama3-8B中与标准微调相比，ECE平均减少了57%。这些改进很好地推广到领域外的任务，增强了特定领域LLMs的客观性和可靠性，使其在关键的人工智能交互应用中更值得信赖。


> Fine-tuned Large Language Models (LLMs) often demonstrate poor calibration, with their confidence scores misaligned with actual performance. While calibration has been extensively studied in models trained from scratch, the impact of LLMs' prior knowledge on calibration during fine-tuning remains understudied. Our research reveals that LLMs' prior knowledge causes potential poor calibration due to the ubiquitous presence of known data in real-world fine-tuning, which appears harmful for calibration. Specifically, data aligned with LLMs' prior knowledge would induce overconfidence, while new knowledge improves calibration. Our findings expose a tension: LLMs' encyclopedic knowledge, while enabling task versatility, undermines calibration through unavoidable knowledge overlaps. To address this, we propose CogCalib, a cognition-aware framework that applies targeted learning strategies according to the model's prior knowledge. Experiments across 7 tasks using 3 LLM families prove that CogCalib significantly improves calibration while maintaining performance, achieving an average 57\% reduction in ECE compared to standard fine-tuning in Llama3-8B. These improvements generalize well to out-of-domain tasks, enhancing the objectivity and reliability of domain-specific LLMs, and making them more trustworthy for critical human-AI interaction applications.

[Arxiv](https://arxiv.org/abs/2505.20903)