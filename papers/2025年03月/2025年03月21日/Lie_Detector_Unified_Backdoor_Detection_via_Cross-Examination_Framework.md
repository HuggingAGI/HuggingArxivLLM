# 欺骗检测器：基于跨审查框架的统一后门检测方案

发布时间：2025年03月21日

`LLM理论` `人工智能安全` `云计算`

> Lie Detector: Unified Backdoor Detection via Cross-Examination Framework

# 摘要

> 数据和计算资源有限的机构通常会将模型训练外包给第三方提供商，并假设这些提供商遵循预定义的学习范式进行训练（如监督学习或半监督学习）。然而，这种做法可能带来严重的安全风险，因为攻击者可能会毒化训练数据，从而在生成的模型中植入后门。现有的检测方法主要依赖统计分析，但这种方法在不同学习范式下常常无法保持检测准确性的普遍性。为了解决这一问题，我们提出了一种在半诚实设置下的统一后门检测框架，该框架通过两个独立服务提供商之间模型不一致性的交叉检查来实现。具体而言，我们整合了中心核对齐技术，以实现不同模型架构和学习范式下鲁棒的特征相似性测量，从而促进后门触发器的精确恢复和识别。我们还引入了后门微调敏感性分析，以区分后门触发器和对抗性扰动，从而大幅减少误报。大量实验表明，我们的方法在监督学习、半监督学习和自回归学习任务中的检测准确率分别比现有最优基线提高了5.4%、1.6%和11.9%。值得注意的是，这是首个能够有效检测多模态大型语言模型中后门的方法，进一步突显了其广泛适用性并推动了安全深度学习的发展。

> Institutions with limited data and computing resources often outsource model training to third-party providers in a semi-honest setting, assuming adherence to prescribed training protocols with pre-defined learning paradigm (e.g., supervised or semi-supervised learning). However, this practice can introduce severe security risks, as adversaries may poison the training data to embed backdoors into the resulting model. Existing detection approaches predominantly rely on statistical analyses, which often fail to maintain universally accurate detection accuracy across different learning paradigms. To address this challenge, we propose a unified backdoor detection framework in the semi-honest setting that exploits cross-examination of model inconsistencies between two independent service providers. Specifically, we integrate central kernel alignment to enable robust feature similarity measurements across different model architectures and learning paradigms, thereby facilitating precise recovery and identification of backdoor triggers. We further introduce backdoor fine-tuning sensitivity analysis to distinguish backdoor triggers from adversarial perturbations, substantially reducing false positives. Extensive experiments demonstrate that our method achieves superior detection performance, improving accuracy by 5.4%, 1.6%, and 11.9% over SoTA baselines across supervised, semi-supervised, and autoregressive learning tasks, respectively. Notably, it is the first to effectively detect backdoors in multimodal large language models, further highlighting its broad applicability and advancing secure deep learning.

[Arxiv](https://arxiv.org/abs/2503.16872)