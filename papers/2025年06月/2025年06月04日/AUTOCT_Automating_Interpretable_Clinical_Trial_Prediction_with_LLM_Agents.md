# AUTOCT：借助LLM代理实现可解释的临床试验预测自动化

发布时间：2025年06月04日

`LLM应用` `临床试验`

> AUTOCT: Automating Interpretable Clinical Trial Prediction with LLM Agents

# 摘要

> 临床试验对推动医学治疗的发展至关重要，但其成本高昂且耗时。准确预测临床试验结果不仅可以显著降低研发成本，还能加速药物发现。然而，尽管最近利用非结构化数据的深度学习模型展现出潜力，但其黑箱特性、缺乏可解释性以及对标签泄露的脆弱性限制了它们在高风险生物医学环境中的实际应用。

在本研究中，我们提出了AutoCT，一个结合大型语言模型推理能力和经典机器学习可解释性的新框架。AutoCT能够基于公共信息自主生成、评估和优化表格特征，无需人工干预。我们的方法利用蒙特卡洛树搜索来迭代优化预测性能。

实验结果表明，AutoCT在临床试验预测任务中表现优异，仅在有限的自我优化迭代次数内，其表现与现有最优方法持平甚至更优。这为临床试验预测提供了一个可扩展、可解释且成本高效的全新范式。

> Clinical trials are critical for advancing medical treatments but remain prohibitively expensive and time-consuming. Accurate prediction of clinical trial outcomes can significantly reduce research and development costs and accelerate drug discovery. While recent deep learning models have shown promise by leveraging unstructured data, their black-box nature, lack of interpretability, and vulnerability to label leakage limit their practical use in high-stakes biomedical contexts. In this work, we propose AutoCT, a novel framework that combines the reasoning capabilities of large language models with the explainability of classical machine learning. AutoCT autonomously generates, evaluates, and refines tabular features based on public information without human input. Our method uses Monte Carlo Tree Search to iteratively optimize predictive performance. Experimental results show that AutoCT performs on par with or better than SOTA methods on clinical trial prediction tasks within only a limited number of self-refinement iterations, establishing a new paradigm for scalable, interpretable, and cost-efficient clinical trial prediction.

[Arxiv](https://arxiv.org/abs/2506.04293)