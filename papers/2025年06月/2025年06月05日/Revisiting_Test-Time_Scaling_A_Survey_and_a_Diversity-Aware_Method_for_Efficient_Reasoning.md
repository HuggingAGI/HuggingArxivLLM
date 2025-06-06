# 重新审视测试时间缩放：一项高效推理的多样性感知方法调查

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了测试时缩放（TTS）方法在提升大型语言模型推理性能方面的应用，提出了ADAPT方法来优化生成的多样性。研究集中在如何优化LLM在实际任务中的表现，属于应用层面的改进。` `数学推理`

> Revisiting Test-Time Scaling: A Survey and a Diversity-Aware Method for Efficient Reasoning

# 摘要

> 测试时缩放（TTS）能通过在推理过程中分配额外计算资源来提升大型语言模型（LLMs）的推理性能。我们对TTS方法进行了系统性梳理，并将其划分为基于采样的、基于搜索的和基于轨迹优化的三类策略。我们发现，专为推理优化的模型通常会产生较为单一的输出结果，这限制了TTS的实际效果。为了解决这一问题，我们提出了ADAPT（一种关注多样性的前缀微调方法），该方法采用了一种以多样性为导向的数据策略，并结合前缀微调技术。实验结果表明，在数学推理任务中，ADAPT方法的准确率达到了80%，且计算量仅为强劲基线模型的八分之一。我们的研究发现凸显了生成多样性在最大化TTS效果中的关键作用。

> Test-Time Scaling (TTS) improves the reasoning performance of Large Language Models (LLMs) by allocating additional compute during inference. We conduct a structured survey of TTS methods and categorize them into sampling-based, search-based, and trajectory optimization strategies. We observe that reasoning-optimized models often produce less diverse outputs, which limits TTS effectiveness. To address this, we propose ADAPT (A Diversity Aware Prefix fine-Tuning), a lightweight method that applies prefix tuning with a diversity-focused data strategy. Experiments on mathematical reasoning tasks show that ADAPT reaches 80% accuracy using eight times less compute than strong baselines. Our findings highlight the essential role of generative diversity in maximizing TTS effectiveness.

[Arxiv](https://arxiv.org/abs/2506.04611)