# 基于前缀的采样融合监督与强化微调

发布时间：2025年07月02日

`LLM理论

摘要讨论了大语言模型的后训练技术，提出了一种结合监督微调和强化微调的新方法。这属于模型训练和优化的理论层面，因此归类为LLM理论。`

> Blending Supervised and Reinforcement Fine-Tuning with Prefix Sampling

# 摘要

> 现有的大语言模型后训练技术主要分为监督微调（SFT）和强化微调（RFT），各有其优缺点。SFT擅长模仿演示数据，但容易导致行为克隆的泛化问题；而RFT虽能显著提升模型性能，却可能学到意外行为，且对初始策略高度敏感。本文提出了一种统一视角，将这两种方法结合起来，提出了Prefix-RFT——一种演示与探索协同学习的混合方法。通过数学推理问题的实证研究，我们发现Prefix-RFT不仅简单有效，还超越了独立SFT和RFT的性能，甚至优于并行混合策略RFT方法。其优势在于能够无缝集成到现有开源框架中，仅需对标准RFT管道进行少量修改。分析表明，SFT和RFT具有互补性，Prefix-RFT成功实现了两者的和谐统一。此外，消融实验进一步验证了该方法对演示数据质量和数量变化的鲁棒性。我们希望这项研究为大语言模型的后训练提供了新思路，表明整合演示与探索的统一范式可能是未来研究的有益方向。

> Existing post-training techniques for large language models are broadly categorized into Supervised Fine-Tuning (SFT) and Reinforcement Fine-Tuning (RFT). Each paradigm presents a distinct trade-off: SFT excels at mimicking demonstration data but can lead to problematic generalization as a form of behavior cloning. Conversely, RFT can significantly enhance a model's performance but is prone to learn unexpected behaviors, and its performance is highly sensitive to the initial policy. In this paper, we propose a unified view of these methods and introduce Prefix-RFT, a hybrid approach that synergizes learning from both demonstration and exploration. Using mathematical reasoning problems as a testbed, we empirically demonstrate that Prefix-RFT is both simple and effective. It not only surpasses the performance of standalone SFT and RFT but also outperforms parallel mixed-policy RFT methods. A key advantage is its seamless integration into existing open-source frameworks, requiring only minimal modifications to the standard RFT pipeline. Our analysis highlights the complementary nature of SFT and RFT, and validates that Prefix-RFT effectively harmonizes these two learning paradigms. Furthermore, ablation studies confirm the method's robustness to variations in the quality and quantity of demonstration data. We hope this work offers a new perspective on LLM post-training, suggesting that a unified paradigm that judiciously integrates demonstration and exploration could be a promising direction for future research.

[Arxiv](https://arxiv.org/abs/2507.01679)