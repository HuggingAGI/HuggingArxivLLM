# 从通用奖励到针对性奖励：在开放式的长上下文生成中超越GPT-4

发布时间：2025年06月19日

`LLM应用` `文本生成`

> From General to Targeted Rewards: Surpassing GPT-4 in Open-Ended Long-Context Generation

# 摘要

> 现有针对大型语言模型中长上下文的研究主要关注理解长上下文，而开放式的长文本生成（Open-LTG）领域仍有许多未探索之处。训练长上下文生成模型需要依赖黄金标准的参考数据，然而对于信息型的Open-LTG任务，这类数据往往难以获取。以往的方法仅使用通用评估作为奖励信号，这在准确性提升方面存在局限。为填补这一研究空白，我们提出了ProxyReward——一个基于强化学习（RL）的创新框架，包含数据集和奖励信号计算方法。首先，ProxyReward数据集的生成通过简单提示语实现，无需大量标注数据或人工干预，模型即可自动完成。其次，ProxyReward信号针对特定问题的信息全面性和准确性进行精准评估。实验结果表明，ProxyReward不仅超越了GPT-4-Turbo的表现，还能使开源模型在Open-LTG任务上的性能提升20%，同时优于将LLM作为评估者的传统方法。我们的研究为提升大型语言模型处理复杂开放性问题的能力提供了切实可行的解决方案。

> Current research on long-form context in Large Language Models (LLMs) primarily focuses on the understanding of long-contexts, the Open-ended Long Text Generation (Open-LTG) remains insufficiently explored. Training a long-context generation model requires curation of gold standard reference data, which is typically nonexistent for informative Open-LTG tasks. However, previous methods only utilize general assessments as reward signals, which limits accuracy. To bridge this gap, we introduce ProxyReward, an innovative reinforcement learning (RL) based framework, which includes a dataset and a reward signal computation method. Firstly, ProxyReward Dataset generation is accomplished through simple prompts that enables the model to create automatically, obviating extensive labeled data or significant manual effort. Secondly, ProxyReward Signal offers a targeted evaluation of information comprehensiveness and accuracy for specific questions. The experimental results indicate that our method ProxyReward surpasses even GPT-4-Turbo. It can significantly enhance performance by 20% on the Open-LTG task when training widely used open-source models, while also surpassing the LLM-as-a-Judge approach. Our work presents effective methods to enhance the ability of LLMs to address complex open-ended questions posed by human.

[Arxiv](https://arxiv.org/abs/2506.16024)