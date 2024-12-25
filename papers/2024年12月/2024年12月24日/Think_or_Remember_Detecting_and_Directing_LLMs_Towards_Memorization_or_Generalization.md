# 思考还是记忆？检测并引导大型语言模型是走向记忆还是泛化

发布时间：2024年12月24日

`LLM理论` `人工智能` `神经科学`

> Think or Remember? Detecting and Directing LLMs Towards Memorization or Generalization

# 摘要

> 在本文中，受人类大脑功能专业化的启发，我们探究了大型语言模型（LLMs）中记忆与泛化的基本机制。我们的研究以专门设计的数据集和实验规模的LLMs为依托展开案例分析，为理解这些行为奠定基础。具体而言，我们首先要通过设计的数据集训练让LLMs兼具记忆和泛化能力，接着（a）考察LLMs在神经元层面是否存在记忆和泛化的空间差异，（b）利用模型内部表征来预测这些行为，（c）通过推理时的干预来引导这些行为。我们的研究结果显示，在LLMs中能够观察到记忆和泛化的神经元级差异，并且有针对性的干预能够成功引导其行为。

> In this paper, we explore the foundational mechanisms of memorization and generalization in Large Language Models (LLMs), inspired by the functional specialization observed in the human brain. Our investigation serves as a case study leveraging specially designed datasets and experimental-scale LLMs to lay the groundwork for understanding these behaviors. Specifically, we aim to first enable LLMs to exhibit both memorization and generalization by training with the designed dataset, then (a) examine whether LLMs exhibit neuron-level spatial differentiation for memorization and generalization, (b) predict these behaviors using model internal representations, and (c) steer the behaviors through inference-time interventions. Our findings reveal that neuron-wise differentiation of memorization and generalization is observable in LLMs, and targeted interventions can successfully direct their behavior.

[Arxiv](https://arxiv.org/abs/2412.18497)