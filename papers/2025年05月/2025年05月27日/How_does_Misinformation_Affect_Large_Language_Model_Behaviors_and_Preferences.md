# 错误信息对大型语言模型的行为和偏好有何影响？

发布时间：2025年05月27日

`LLM应用` `错误信息检测` `信息检索`

> How does Misinformation Affect Large Language Model Behaviors and Preferences?

# 摘要

> 大型语言模型（LLMs）在知识密集型任务中表现出了非凡的能力，但它们在处理错误信息时仍显脆弱。尽管现有研究探讨了LLMs在对抗错误信息中的作用，但对其受影响的具体方面和程度的细致分析仍有待深入。为解决这一问题，我们推出了MisBench——目前规模最大、内容最全面的基准测试，旨在评估LLMs在面对错误信息时的行为和知识偏好。MisBench收录了10,346,712条错误信息，其独特之处在于同时考虑了知识冲突和风格变化这两大关键因素。实证研究表明，LLMs在辨别错误信息方面的能力相当，但它们仍易受知识冲突和风格变化的影响。基于这一发现，我们提出了一种名为Reconstruct to Discriminate（RtD）的创新方法，以提升LLMs检测错误信息的能力。本研究为理解LLMs与错误信息的交互提供了深刻的见解，我们相信MisBench将成为评估基于LLMs的检测器并提升其实际应用可靠性的重要基准。相关代码和数据已开源，可在GitHub上获取。

> Large Language Models (LLMs) have shown remarkable capabilities in knowledge-intensive tasks, while they remain vulnerable when encountering misinformation. Existing studies have explored the role of LLMs in combating misinformation, but there is still a lack of fine-grained analysis on the specific aspects and extent to which LLMs are influenced by misinformation. To bridge this gap, we present MisBench, the current largest and most comprehensive benchmark for evaluating LLMs' behavior and knowledge preference toward misinformation. MisBench consists of 10,346,712 pieces of misinformation, which uniquely considers both knowledge-based conflicts and stylistic variations in misinformation. Empirical results reveal that while LLMs demonstrate comparable abilities in discerning misinformation, they still remain susceptible to knowledge conflicts and stylistic variations. Based on these findings, we further propose a novel approach called Reconstruct to Discriminate (RtD) to strengthen LLMs' ability to detect misinformation. Our study provides valuable insights into LLMs' interactions with misinformation, and we believe MisBench can serve as an effective benchmark for evaluating LLM-based detectors and enhancing their reliability in real-world applications. Codes and data are available at https://github.com/GKNL/MisBench.

[Arxiv](https://arxiv.org/abs/2505.21608)