# 教大型语言模型学会推理：从学习到遗忘的艺术

发布时间：2025年04月15日

`LLM理论

理由：这篇论文探讨了如何通过改进大型语言模型的推理机制来提升其解决复杂问题的能力，属于模型理论层面的研究。` `人工智能` `模型优化`

> Teaching Large Language Models to Reason through Learning and Forgetting

# 摘要

> 在大型语言模型中，通过推理时搜索进一步提升模型解决复杂数学与推理问题的能力已被证实行之有效。然而，这种方法大幅增加了计算成本和推理时间，因为模型需要生成并评估多个候选方案以找到可行的推理路径。针对这一挑战，我们提出了一种创新方法，通过巧妙整合多种搜索方法的成功与失败推理路径（分别对应学习与遗忘），并对模型进行微调，将搜索能力直接嵌入模型。尽管这一思路看似简单，但我们在实践中发现了一个关键问题：若进行盲目微调，模型的搜索能力往往会迅速退化。我们发现，采用较小的学习率可以显著缓解这一问题。在具有挑战性的24点游戏和倒计时数学推理基准测试中，我们的方法不仅超越了标准微调和推理时搜索的基线表现，更将推理时间大幅降低180倍。

> Leveraging inference-time search in large language models has proven effective in further enhancing a trained model's capability to solve complex mathematical and reasoning problems. However, this approach significantly increases computational costs and inference time, as the model must generate and evaluate multiple candidate solutions to identify a viable reasoning path. To address this, we propose an effective approach that integrates search capabilities directly into the model by fine-tuning it using both successful (learning) and failed reasoning paths (forgetting) derived from diverse search methods. While fine-tuning the model with these data might seem straightforward, we identify a critical issue: the model's search capability tends to degrade rapidly if fine-tuning is performed naively. We show that this degradation can be substantially mitigated by employing a smaller learning rate. Extensive experiments on the challenging Game-of-24 and Countdown mathematical reasoning benchmarks show that our approach not only outperforms both standard fine-tuning and inference-time search baselines but also significantly reduces inference time by 180$\times$.

[Arxiv](https://arxiv.org/abs/2504.11364)