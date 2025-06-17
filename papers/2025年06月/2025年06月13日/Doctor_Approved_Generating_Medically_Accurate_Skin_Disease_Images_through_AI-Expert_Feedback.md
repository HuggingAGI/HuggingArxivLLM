# 医学专家认可：AI生成精准皮肤病图像，助力临床诊断

发布时间：2025年06月13日

`LLM应用`

> Doctor Approved: Generating Medically Accurate Skin Disease Images through AI-Expert Feedback

# 摘要

> 医学数据的匮乏严重限制了诊断模型的泛化能力，因为小规模临床数据集无法完整呈现疾病的全谱变异。为解决这一问题，扩散模型（DMs）被视作合成图像生成与增强的有前途方案。然而，它们常常生成医学上不准确的图像，损害了模型性能。在数据稀缺且质量重于数量的情况下，专家领域的知识对于生成准确编码临床信息的医学图像至关重要。现有整合人类反馈的方法，如强化学习（RL）和直接偏好优化（DPO），依赖于稳健的奖励函数或需要耗时的专家评估。多模态大型语言模型（MLLMs）近期的进展揭示了它们强大的视觉推理能力，使其成为理想的评估者。在本研究中，我们提出了一种创新框架——通过AI与专家协作实现医学图像精准生成的MAGIC（Medically Accurate Generation of Images through AI-Expert Collaboration），用于合成临床准确的皮肤病图像以进行数据增强。我们的方法巧妙地将专家定义的标准转化为扩散模型图像合成的具体反馈，显著提升临床准确性的同时大幅减少直接人工工作量。实验表明，我们的方法极大地提升了合成皮肤病图像的临床质量，输出结果与皮肤科医生的评估相吻合。此外，利用这些合成图像增强训练数据，在一项具有挑战性的20种皮肤病分类任务中，诊断准确率提升了+9.02%，在少量样本场景下更是提升了+13.89%。

> Paucity of medical data severely limits the generalizability of diagnostic ML models, as the full spectrum of disease variability can not be represented by a small clinical dataset. To address this, diffusion models (DMs) have been considered as a promising avenue for synthetic image generation and augmentation. However, they frequently produce medically inaccurate images, deteriorating the model performance. Expert domain knowledge is critical for synthesizing images that correctly encode clinical information, especially when data is scarce and quality outweighs quantity. Existing approaches for incorporating human feedback, such as reinforcement learning (RL) and Direct Preference Optimization (DPO), rely on robust reward functions or demand labor-intensive expert evaluations. Recent progress in Multimodal Large Language Models (MLLMs) reveals their strong visual reasoning capabilities, making them adept candidates as evaluators. In this work, we propose a novel framework, coined MAGIC (Medically Accurate Generation of Images through AI-Expert Collaboration), that synthesizes clinically accurate skin disease images for data augmentation. Our method creatively translates expert-defined criteria into actionable feedback for image synthesis of DMs, significantly improving clinical accuracy while reducing the direct human workload. Experiments demonstrate that our method greatly improves the clinical quality of synthesized skin disease images, with outputs aligning with dermatologist assessments. Additionally, augmenting training data with these synthesized images improves diagnostic accuracy by +9.02% on a challenging 20-condition skin disease classification task, and by +13.89% in the few-shot setting.

[Arxiv](https://arxiv.org/abs/2506.12323)