# # 对抗攻击在机器人视觉语言动作模型中的研究与应用

发布时间：2025年06月03日

`LLM应用` `机器人学` `人工智能`

> Adversarial Attacks on Robotic Vision Language Action Models

# 摘要

> 视觉-语言-动作模型（VLAs）的出现正在通过在数十亿参数规模上融合多模态感官输入，重塑机器人学领域的格局。VLAs的能力主要源于其架构，这些架构通常基于前沿的大型语言模型（LLMs）。然而，LLMs众所周知容易受到对抗性滥用，考虑到机器人学中固有的重大物理风险，VLAs继承这些漏洞的程度仍存在疑问。出于这些担忧，本研究旨在探索针对由VLA控制的机器人的对抗性攻击。我们的主要算法贡献是将LLM越狱攻击适应并应用于获取对VLAs的完全控制权限。我们发现，文本攻击——即在 rollout 开始时一次性应用的攻击——能够实现对常用 VLAs 动作空间的完全可达性，并且往往在更长的时间范围内持续有效。这与现有的 LLM 越狱文献显著不同，因为在现实世界中，攻击不必在语义上与伤害的概念相关联。我们将在 https://github.com/eliotjones1/robogcg 上开放所有代码。


> The emergence of vision-language-action models (VLAs) for end-to-end control is reshaping the field of robotics by enabling the fusion of multimodal sensory inputs at the billion-parameter scale. The capabilities of VLAs stem primarily from their architectures, which are often based on frontier large language models (LLMs). However, LLMs are known to be susceptible to adversarial misuse, and given the significant physical risks inherent to robotics, questions remain regarding the extent to which VLAs inherit these vulnerabilities. Motivated by these concerns, in this work we initiate the study of adversarial attacks on VLA-controlled robots. Our main algorithmic contribution is the adaptation and application of LLM jailbreaking attacks to obtain complete control authority over VLAs. We find that textual attacks, which are applied once at the beginning of a rollout, facilitate full reachability of the action space of commonly used VLAs and often persist over longer horizons. This differs significantly from LLM jailbreaking literature, as attacks in the real world do not have to be semantically linked to notions of harm. We make all code available at https://github.com/eliotjones1/robogcg .

[Arxiv](https://arxiv.org/abs/2506.03350)