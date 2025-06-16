# Med-PRM：基于分步指南验证流程奖励的医疗推理模型

发布时间：2025年06月13日

`LLM应用` `临床决策支持系统`

> Med-PRM: Medical Reasoning Models with Stepwise, Guideline-verified Process Rewards

# 摘要

> 大型语言模型在临床决策支持方面展现出巨大潜力，但现有方法在推理过程中的特定步骤定位和修正错误方面仍存在困难。这一问题在医学领域尤为重要，因为准确诊断和有效治疗需要及时发现并纠正推理中的错误。我们提出了Med-PRM，一个基于检索增强生成的过程奖励建模框架，通过与权威医学知识库进行对比，逐层验证推理过程。利用从临床指南和医学文献中检索到的证据，Med-PRM能够以细致入微的方式评估推理质量。在五个医疗问答基准测试和两个开放性诊断任务上的实证研究表明，Med-PRM实现了当前最佳性能，使基础模型的性能提升高达13.50%。此外，我们将Med-PRM以即插即用的方式与强策略模型（如Meerkat）相结合，首次在MedQA任务中实现了超过80%的准确率，且仅使用了80亿参数的小规模模型。我们的代码和数据已公开，访问地址为：https://med-prm.github.io/

> Large language models have shown promise in clinical decision making, but current approaches struggle to localize and correct errors at specific steps of the reasoning process. This limitation is critical in medicine, where identifying and addressing reasoning errors is essential for accurate diagnosis and effective patient care. We introduce Med-PRM, a process reward modeling framework that leverages retrieval-augmented generation to verify each reasoning step against established medical knowledge bases. By verifying intermediate reasoning steps with evidence retrieved from clinical guidelines and literature, our model can precisely assess the reasoning quality in a fine-grained manner. Evaluations on five medical QA benchmarks and two open-ended diagnostic tasks demonstrate that Med-PRM achieves state-of-the-art performance, with improving the performance of base models by up to 13.50% using Med-PRM. Moreover, we demonstrate the generality of Med-PRM by integrating it in a plug-and-play fashion with strong policy models such as Meerkat, achieving over 80\% accuracy on MedQA for the first time using small-scale models of 8 billion parameters. Our code and data are available at: https://med-prm.github.io/

[Arxiv](https://arxiv.org/abs/2506.11474)