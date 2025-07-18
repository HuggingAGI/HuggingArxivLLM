# 洞察专为放射学设计的多模态大型语言模型，融合稀疏自编码器技术

发布时间：2025年07月17日

`LLM理论` `放射学`

> Insights into a radiology-specialised multimodal large language model with sparse autoencoders

# 摘要

> 可解释性对提升AI模型的安全性、透明度和可信度至关重要，尤其在医疗领域，因为决策往往影响深远。借助稀疏自动编码器（SAEs），我们找到了一种有效方法，能够在大型基于变压器的模型中揭示人类可理解的特征。本研究将Matryoshka-SAE应用于专注于放射学的多模态大型语言模型MAIRA-2，深入解析其内部表示。通过对SAE特征进行大规模自动化分析，我们识别出众多临床相关概念，涵盖医疗设备（如导管和起搏器）、病症（如胸腔积液和心脏肥大）、纵向变化和文本特征。通过引导方法，我们还探索了这些特征对模型行为的影响，成功实现了对生成结果的方向性控制。尽管面临实际和方法上的挑战，我们的研究为理解MAIRA-2的学习机制提供了重要见解，推动了放射学领域多模态大型语言模型的可解释性和透明度。我们已发布经过训练的SAEs和解释：https://huggingface.co/microsoft/maira-2-sae。

> Interpretability can improve the safety, transparency and trust of AI models, which is especially important in healthcare applications where decisions often carry significant consequences. Mechanistic interpretability, particularly through the use of sparse autoencoders (SAEs), offers a promising approach for uncovering human-interpretable features within large transformer-based models. In this study, we apply Matryoshka-SAE to the radiology-specialised multimodal large language model, MAIRA-2, to interpret its internal representations. Using large-scale automated interpretability of the SAE features, we identify a range of clinically relevant concepts - including medical devices (e.g., line and tube placements, pacemaker presence), pathologies such as pleural effusion and cardiomegaly, longitudinal changes and textual features. We further examine the influence of these features on model behaviour through steering, demonstrating directional control over generations with mixed success. Our results reveal practical and methodological challenges, yet they offer initial insights into the internal concepts learned by MAIRA-2 - marking a step toward deeper mechanistic understanding and interpretability of a radiology-adapted multimodal large language model, and paving the way for improved model transparency. We release the trained SAEs and interpretations: https://huggingface.co/microsoft/maira-2-sae.

[Arxiv](https://arxiv.org/abs/2507.12950)