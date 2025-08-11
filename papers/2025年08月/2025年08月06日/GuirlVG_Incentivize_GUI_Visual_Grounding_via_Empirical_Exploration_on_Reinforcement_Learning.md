# GuirlVG: 基于强化学习的 GUI 视觉定位激励探索

发布时间：2025年08月06日

`强化学习` `图形用户界面` `人工智能`

> GuirlVG: Incentivize GUI Visual Grounding via Empirical Exploration on Reinforcement Learning

# 摘要

> 图形用户界面视觉定位（GUI-VG）作为GUI代理的核心能力，传统上主要依赖于多模态大型语言模型（MLLMs）的监督微调（SFT），这种方法需要大量数据整理和高昂的训练成本。然而，随着MLLMs的不断进步，甚至在预训练阶段就涵盖了GUI领域，这种耗时耗力的SFT后训练方法的必要性变得越来越值得怀疑。与此同时，基于规则的强化微调（RFT）近期的成功表明了一种更高效的替代方案。尽管如此，如何将RFT最佳地应用于GUI-VG仍是一个未解之谜。为了填补这一空白，我们引入了GuirlVG，这是一种基于强化学习的GUI-VG方法，建立在系统性实证研究和一项创新的稳定技术之上。我们发现，简单地将RFT应用于GUI-VG的表现不如SFT基准，这促使我们进行了更深入的探索。首先，我们将RFT分解为其核心组件，并分析了每个组件的最佳实现方式。其次，我们提出了一种新型的对抗KL因子，能够动态稳定训练过程，以缓解奖励过优问题。第三，我们进一步探索了RFT的训练配置，以提高其有效性。大量实验表明，GuirlVG仅使用5.2K训练样本，便超越了基于超过1000万个样本训练的SFT方法，在ScreenSpot上实现了7.7%的提升，在ScreenSpotPro上实现了17.2%的提升，并在ScreenSpotV2上达到了91.9%的准确率。

> Graphical user interface visual grounding (GUI-VG), a core capability for GUI agents, has primarily relied on supervised fine-tuning (SFT) of multimodal large language models (MLLMs), which demands extensive data curation and significant training costs. However, as MLLMs continue to advance and even cover GUI domains during pretraining, the necessity of exhaustive SFT post-training becomes increasingly questionable. Meanwhile, recent successes of rule-based reinforcement fine-tuning (RFT) suggest a more efficient alternative. Despite this promise, the optimal manner of applying RFT for GUI-VG remains unexplored. To bridge this gap, we introduce GuirlVG, a reinforcement learning-based GUI-VG method built on a systematic empirical study and a novel stabilization technique. We find that naive application of RFT underperforms the SFT baseline, motivating a deeper exploration. First, we decompose RFT into its core components and analyze the optimal formulation of each. Second, we propose a novel Adversarial KL Factor that dynamically stabilizes training to mitigate reward over-optimization. Third, we further explore the training configurations of RFT to enhance effectiveness. Extensive experiments show that GuirlVG, with only 5.2K training samples, outperforms SFT methods trained on over 10M samples, achieving a 7.7% improvement on ScreenSpot, a 17.2% improvement on ScreenSpotPro, and 91.9% accuracy on ScreenSpotV2.

[Arxiv](https://arxiv.org/abs/2508.04389)