# U-GIFT: 少样本场景下基于不确定性引导的有毒言论防火墙

发布时间：2025年01月01日

`LLM应用

**解释**：这篇论文主要讨论了利用自训练和贝叶斯神经网络（BNNs）来提升少样本场景下的有毒言论检测性能。虽然论文中提到了预训练语言模型（PLMs），但核心内容集中在如何利用这些模型进行具体的应用（即有毒言论检测），而不是对LLM本身的理论研究或改进。因此，将其分类为LLM应用更为合适。` `社交媒体` `网络安全`

> U-GIFT: Uncertainty-Guided Firewall for Toxic Speech in Few-Shot Scenario

# 摘要

> 随着社交媒体的普及，用户生成内容在在线平台上激增。当这些内容涉及仇恨、辱骂、冒犯或网络欺凌时，便被归类为有毒言论，严重威胁在线生态系统的完整性和安全。尽管手动内容审核仍占主导，但海量内容和对审核员的心理压力凸显了自动化有毒言论检测的迫切需求。以往检测方法多依赖大规模标注数据集，然而获取此类数据集成本高且难度大。为此，我们提出了一种少样本场景下的不确定性引导防火墙U-GIFT，利用自训练提升检测性能，即便在标注数据有限的情况下。具体而言，U-GIFT结合主动学习与贝叶斯神经网络（BNNs），自动从未标注数据中筛选高质量样本，优先选择基于模型预测不确定性估计的高置信度伪标签进行训练。大量实验表明，U-GIFT在少样本检测场景中显著优于竞争基线。在5-shot设置下，其性能较基础模型提升14.92%。尤为重要的是，U-GIFT用户友好，适配多种预训练语言模型（PLMs），在样本不平衡和跨域场景中表现稳健，并在多种语言应用中展现出强大的泛化能力。我们相信，U-GIFT为少样本有毒言论检测提供了高效解决方案，为网络空间自动化内容审核提供了有力支持，作为防火墙推动了网络安全的进步。

> With the widespread use of social media, user-generated content has surged on online platforms. When such content includes hateful, abusive, offensive, or cyberbullying behavior, it is classified as toxic speech, posing a significant threat to the online ecosystem's integrity and safety. While manual content moderation is still prevalent, the overwhelming volume of content and the psychological strain on human moderators underscore the need for automated toxic speech detection. Previously proposed detection methods often rely on large annotated datasets; however, acquiring such datasets is both costly and challenging in practice. To address this issue, we propose an uncertainty-guided firewall for toxic speech in few-shot scenarios, U-GIFT, that utilizes self-training to enhance detection performance even when labeled data is limited. Specifically, U-GIFT combines active learning with Bayesian Neural Networks (BNNs) to automatically identify high-quality samples from unlabeled data, prioritizing the selection of pseudo-labels with higher confidence for training based on uncertainty estimates derived from model predictions. Extensive experiments demonstrate that U-GIFT significantly outperforms competitive baselines in few-shot detection scenarios. In the 5-shot setting, it achieves a 14.92\% performance improvement over the basic model. Importantly, U-GIFT is user-friendly and adaptable to various pre-trained language models (PLMs). It also exhibits robust performance in scenarios with sample imbalance and cross-domain settings, while showcasing strong generalization across various language applications. We believe that U-GIFT provides an efficient solution for few-shot toxic speech detection, offering substantial support for automated content moderation in cyberspace, thereby acting as a firewall to promote advancements in cybersecurity.

[Arxiv](https://arxiv.org/abs/2501.00907)