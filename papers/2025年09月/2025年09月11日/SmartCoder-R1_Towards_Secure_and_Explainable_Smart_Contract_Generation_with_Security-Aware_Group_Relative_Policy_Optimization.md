# SmartCoder-R1：致力于安全可解释的智能合约生成——借助安全感知的群体相对策略优化

发布时间：2025年09月11日

`LLM应用` `金融科技`

> SmartCoder-R1: Towards Secure and Explainable Smart Contract Generation with Security-Aware Group Relative Policy Optimization

# 摘要

> 智能合约负责高价值资产的自动化管理，一旦存在漏洞，就可能造成灾难性的财务损失。而在大型语言模型（LLMs）中，这一挑战因两个相互关联的问题而更为严峻：它们如同不可审计的“黑箱”，缺乏透明的推理过程，因此生成的代码往往存在严重的安全漏洞。为同时解决这两个问题，我们提出了SmartCoder-R1（基于Qwen2.5-Coder-7B）——一个用于安全且可解释的智能合约生成的全新框架。该框架首先通过持续预训练（CPT）对模型进行专项优化；接着，在7998个专家验证的推理与代码样本上应用长思维链监督微调（L-CoT SFT），训练模型模拟人类的安全分析过程；最后，为直接缓解漏洞问题，引入安全感知组相对策略优化（S-GRPO）——这一强化学习阶段通过优化编译成功、安全合规及格式正确性的加权奖励信号，进一步完善生成策略。在包含756个真实世界函数的基准测试中，SmartCoder-R1与17个基线模型相比创下新的技术标杆，在五项关键指标上均表现最佳：ComPass达87.70%、VulRate为8.60%、SafeAval为80.16%、FuncRate为53.84%，FullRate则为50.53%。其中，FullRate较最强基线模型DeepSeek-R1相对提升了45.79%。尤为关键的是，其生成的推理过程在人类评估中同样表现卓越，在功能性（82.7%）、安全性（85.3%）和清晰度（90.7%）上均获得了高质量评分。

> Smart contracts automate the management of high-value assets, where vulnerabilities can lead to catastrophic financial losses. This challenge is amplified in Large Language Models (LLMs) by two interconnected failures: they operate as unauditable "black boxes" lacking a transparent reasoning process, and consequently, generate code riddled with critical security vulnerabilities. To address both issues, we propose SmartCoder-R1 (based on Qwen2.5-Coder-7B), a novel framework for secure and explainable smart contract generation. It begins with Continual Pre-training (CPT) to specialize the model. We then apply Long Chain-of-Thought Supervised Fine-Tuning (L-CoT SFT) on 7,998 expert-validated reasoning-and-code samples to train the model to emulate human security analysis. Finally, to directly mitigate vulnerabilities, we employ Security-Aware Group Relative Policy Optimization (S-GRPO), a reinforcement learning phase that refines the generation policy by optimizing a weighted reward signal for compilation success, security compliance, and format correctness. Evaluated against 17 baselines on a benchmark of 756 real-world functions, SmartCoder-R1 establishes a new state of the art, achieving top performance across five key metrics: a ComPass of 87.70%, a VulRate of 8.60%, a SafeAval of 80.16%, a FuncRate of 53.84%, and a FullRate of 50.53%. This FullRate marks a 45.79% relative improvement over the strongest baseline, DeepSeek-R1. Crucially, its generated reasoning also excels in human evaluations, achieving high-quality ratings for Functionality (82.7%), Security (85.3%), and Clarity (90.7%).

[Arxiv](https://arxiv.org/abs/2509.09942)