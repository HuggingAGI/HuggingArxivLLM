# 通过对抗训练识别LLM生成代码的微小改动

发布时间：2025年07月17日

`LLM应用` `软件工程` `代码生成`

> Detecting LLM-generated Code with Subtle Modification by Adversarial Training

# 摘要

> 大型语言模型（LLMs）的迅猛发展使其代码生成能力在代码补全和自动化开发等领域大放异彩，显著提升了编码效率。然而，LLM生成代码的广泛应用也带来诸多挑战。一方面，代码出处监管、版权纠纷及代码质量问题日益凸显，如何有效检测LLM生成代码并确保其合规使用成为亟待解决的关键问题。另一方面，实际应用中，LLM生成代码常需手动修改，如变量重命名或结构调整。尽管已有研究提出了基于训练和零-shot的检测方法，但这些方法在应对修改后的LLM生成代码时表现欠佳，缺乏有效解决方案。针对这一现实场景，我们推出了CodeGPTSensor+，这是CodeGPTSensor的升级版，通过对抗训练显著提升了模型的鲁棒性。CodeGPTSensor+引入了Multi-objective Identifier and Structure Transformation (MIST)模块，该模块能系统生成高质量且具代表性的对抗样本，有效增强了模型的抗攻击能力。实验结果表明，相较于CodeGPTSensor，CodeGPTSensor+在对抗测试集上检测准确率大幅提升，同时保持了在原始测试集上的高准确率，展现出更卓越的鲁棒性。

> With the rapid development of Large Language Models (LLMs), their powerful code-generation capabilities have been widely applied in tasks like code completion and automated development, demonstrating the value of improving coding efficiency. However, the extensive use of LLM-generated code also raises several new challenges. On the one hand, issues such as the regulation of code provenance, copyright disputes, and code quality have become increasingly concerning. How to effectively detect LLM-generated code and ensure its compliant and responsible use has become a critical and urgent issue. On the other hand, in practical applications, LLM-generated code is often subject to manual modifications, such as variable renaming or structural adjustments. Although some recent studies have proposed training-based and zero-shot methods for detecting LLM-generated code, these approaches show insufficient robustness when facing modified LLM-generated code, and there is a lack of an effective solution. To address the real-world scenario where LLM-generated code may undergo minor modifications, we propose CodeGPTSensor+, an enhanced version of CodeGPTSensor, which employs adversarial training to improve robustness against input perturbations. CodeGPTSensor+ integrates an adversarial sample generation module, Multi-objective Identifier and Structure Transformation (MIST), which systematically generates both high-quality and representative adversarial samples. This module effectively enhances the model's resistance against diverse adversarial attacks. Experimental results on the HMCorp dataset demonstrate that CodeGPTSensor+ significantly improves detection accuracy on the adversarial test set while maintaining high accuracy on the original test set, showcasing superior robustness compared to CodeGPTSensor.

[Arxiv](https://arxiv.org/abs/2507.13123)