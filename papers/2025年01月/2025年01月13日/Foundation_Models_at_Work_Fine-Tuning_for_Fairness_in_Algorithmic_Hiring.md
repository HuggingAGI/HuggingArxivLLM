# # 工作中的基础模型：算法招聘公平性微调

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了如何通过微调大型语言模型（LLM）来解决特定任务中的问题，特别是通过AutoRefine方法优化生成结果以应对语言偏见。这属于LLM在实际应用中的具体使用场景，因此归类为“LLM应用”。` `推荐系统`

> Foundation Models at Work: Fine-Tuning for Fairness in Algorithmic Hiring

# 摘要

> 基础模型需要通过微调来确保其生成结果与特定任务的目标一致。然而，自动化这一过程颇具挑战，因为它通常依赖昂贵的人工反馈。我们提出了AutoRefine，一种基于强化学习的微调方法，通过特定下游任务中的性能改进直接反馈进行优化。我们以算法招聘平台为例，展示了该方法如何应对语言偏见对推荐系统的影响。生成模型通过重写职位描述，从推荐引擎中获得更多样化的候选人匹配。我们的模型能够检测并调节职位描述中的偏见，确保多样性和公平性。在公共招聘数据集和实际平台上的实验表明，大型语言模型能够有效识别并缓解现实世界中的偏见。

> Foundation models require fine-tuning to ensure their generative outputs align with intended results for specific tasks. Automating this fine-tuning process is challenging, as it typically needs human feedback that can be expensive to acquire. We present AutoRefine, a method that leverages reinforcement learning for targeted fine-tuning, utilizing direct feedback from measurable performance improvements in specific downstream tasks. We demonstrate the method for a problem arising in algorithmic hiring platforms where linguistic biases influence a recommendation system. In this setting, a generative model seeks to rewrite given job specifications to receive more diverse candidate matches from a recommendation engine which matches jobs to candidates. Our model detects and regulates biases in job descriptions to meet diversity and fairness criteria. The experiments on a public hiring dataset and a real-world hiring platform showcase how large language models can assist in identifying and mitigation biases in the real world.

[Arxiv](https://arxiv.org/abs/2501.07324)