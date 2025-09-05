# 借助大型语言模型先验，我们能拯救多少患者？

发布时间：2025年09月04日

`LLM应用` `医疗健康`

> How many patients could we save with LLM priors?

# 摘要

> 试想这样一个世界：得益于大型语言模型（LLMs）中蕴含的知识，临床试验只需远 fewer 患者就能达到相同的统计效力。我们提出了一个用于多中心临床试验不良事件分层贝叶斯建模的全新框架，借助LLM辅助的先验分布。与生成合成数据的数据增强方法不同，我们的方法直接从模型中获取参数化先验。我们的方法利用预训练的LLM，系统性地提取分层贝叶斯模型中超参数的信息先验，实现了外部临床专业知识与贝叶斯安全性建模的直接融合。通过全面的温度敏感性分析和基于真实临床试验数据的严格交叉验证，我们证实LLM衍生的先验相比传统元分析方法，能持续提升预测性能。这种方法为更高效、更贴合专家经验的临床试验设计奠定了基础，大幅减少了实现可靠安全性评估所需的患者数量，并有望革新药物安全监测与监管决策。

> Imagine a world where clinical trials need far fewer patients to achieve the same statistical power, thanks to the knowledge encoded in large language models (LLMs). We present a novel framework for hierarchical Bayesian modeling of adverse events in multi-center clinical trials, leveraging LLM-informed prior distributions. Unlike data augmentation approaches that generate synthetic data points, our methodology directly obtains parametric priors from the model. Our approach systematically elicits informative priors for hyperparameters in hierarchical Bayesian models using a pre-trained LLM, enabling the incorporation of external clinical expertise directly into Bayesian safety modeling. Through comprehensive temperature sensitivity analysis and rigorous cross-validation on real-world clinical trial data, we demonstrate that LLM-derived priors consistently improve predictive performance compared to traditional meta-analytical approaches. This methodology paves the way for more efficient and expert-informed clinical trial design, enabling substantial reductions in the number of patients required to achieve robust safety assessment and with the potential to transform drug safety monitoring and regulatory decision making.

[Arxiv](https://arxiv.org/abs/2509.04250)