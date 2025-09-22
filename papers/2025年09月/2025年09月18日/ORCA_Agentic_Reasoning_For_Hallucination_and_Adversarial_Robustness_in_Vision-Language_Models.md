# ORCA：针对视觉-语言模型幻觉与对抗鲁棒性的智能体推理

发布时间：2025年09月18日

`Agent` `基础理论`

> ORCA: Agentic Reasoning For Hallucination and Adversarial Robustness in Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）具备强大的多模态能力，但仍易受内在错误导致的幻觉和外部恶意攻击的影响，这制约了其在实际场景中的可靠性。为此，我们提出ORCA——一种智能体推理框架，它借助测试时的结构化推理（使用一系列参数少于30亿的小型视觉模型），提升预训练LVLMs的事实准确性与对抗鲁棒性。ORCA的工作机制为“观察-推理-批判-行动”循环：通过证据性问题查询多个视觉工具，校验跨模型不一致性，并在无需访问模型内部或重新训练的情况下迭代优化预测结果。同时，ORCA会记录中间推理过程，为可审计决策提供支持。尽管ORCA的初衷是缓解对象级幻觉，但它还能自然涌现对抗鲁棒性，且无需对抗训练或额外防御机制。我们从三个维度对ORCA进行评估：（1）幻觉基准测试中的干净图像；（2）未加防御的对抗性扰动图像；（3）已加防御的对抗性扰动图像。结果显示：在POPE幻觉基准测试中，ORCA在不同子集上使独立LVLM的性能提升了3.64%至40.67%；在POPE的对抗性扰动场景中，ORCA在不同LVLM上的平均准确率提升达20.11%；而在对抗性扰动的AMBER图像上与防御技术结合使用时，ORCA进一步提升独立LVLM的性能，在各评估指标上的提升幅度达1.20%至48.00%。上述结果表明，ORCA为构建更可靠、更鲁棒的多模态系统开辟了新路径。

> Large Vision-Language Models (LVLMs) exhibit strong multimodal capabilities but remain vulnerable to hallucinations from intrinsic errors and adversarial attacks from external exploitations, limiting their reliability in real-world applications. We present ORCA, an agentic reasoning framework that improves the factual accuracy and adversarial robustness of pretrained LVLMs through test-time structured inference reasoning with a suite of small vision models (less than 3B parameters). ORCA operates via an Observe--Reason--Critique--Act loop, querying multiple visual tools with evidential questions, validating cross-model inconsistencies, and refining predictions iteratively without access to model internals or retraining. ORCA also stores intermediate reasoning traces, which supports auditable decision-making. Though designed primarily to mitigate object-level hallucinations, ORCA also exhibits emergent adversarial robustness without requiring adversarial training or defense mechanisms. We evaluate ORCA across three settings: (1) clean images on hallucination benchmarks, (2) adversarially perturbed images without defense, and (3) adversarially perturbed images with defense applied. On the POPE hallucination benchmark, ORCA improves standalone LVLM performance by +3.64\% to +40.67\% across different subsets. Under adversarial perturbations on POPE, ORCA achieves an average accuracy gain of +20.11\% across LVLMs. When combined with defense techniques on adversarially perturbed AMBER images, ORCA further improves standalone LVLM performance, with gains ranging from +1.20\% to +48.00\% across evaluation metrics. These results demonstrate that ORCA offers a promising path toward building more reliable and robust multimodal systems.

[Arxiv](https://arxiv.org/abs/2509.15435)