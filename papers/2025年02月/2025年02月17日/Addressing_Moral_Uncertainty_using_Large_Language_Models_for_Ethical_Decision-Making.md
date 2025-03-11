# # 利用大型语言模型解决道德不确定性以实现伦理决策
# Addressing Moral Uncertainty using Large Language Models for Ethical Decision-Making

道德不确定性是伦理决策中的常见挑战。大型语言模型（LLMs）通过模拟人类语言的复杂性，为解决这一难题提供了新的可能性。本研究探讨了LLMs在处理道德不确定性方面的应用，旨在为伦理决策提供更加智能化和人性化的解决方案。

发布时间：2025年02月17日

`LLM应用` `人工智能伦理`

> Addressing Moral Uncertainty using Large Language Models for Ethical Decision-Making

# 摘要

> 我们提出了一种伦理决策框架，通过与任务无关的伦理层优化预训练的强化学习（RL）模型。在初始训练后，RL模型会经历伦理微调，其中人类反馈被大型语言模型（LLM）生成的反馈取代。LLM以功利主义、义务论、美德论、社会正义和关怀伦理作为道德原则，在伦理决策过程中为推荐行为分配信念值。伦理层通过信念Jensen-Shannon散度和Dempster-Shafer理论，将多个LLM衍生的道德视角的信念分数聚合为概率分数，这些概率分数也作为塑造奖励，引导代理做出符合平衡伦理框架的选择。这个综合学习框架帮助RL代理在复杂环境中应对道德不确定性，并使其能够在各种任务中做出道德上合理的决策。我们的方法经过不同LLM变体的测试，并与其他信念聚合技术进行了比较，展示了改进的一致性、适应性和对人工设计伦理奖励的减少依赖。该方法在动态场景中特别有效，其中伦理挑战可能意外出现，使其非常适合实际应用。

> We present an ethical decision-making framework that refines a pre-trained reinforcement learning (RL) model using a task-agnostic ethical layer. Following initial training, the RL model undergoes ethical fine-tuning, where human feedback is replaced by feedback generated from a large language model (LLM). The LLM embodies consequentialist, deontological, virtue, social justice, and care ethics as moral principles to assign belief values to recommended actions during ethical decision-making. An ethical layer aggregates belief scores from multiple LLM-derived moral perspectives using Belief Jensen-Shannon Divergence and Dempster-Shafer Theory into probability scores that also serve as the shaping reward, steering the agent toward choices that align with a balanced ethical framework. This integrated learning framework helps the RL agent navigate moral uncertainty in complex environments and enables it to make morally sound decisions across diverse tasks. Our approach, tested across different LLM variants and compared with other belief aggregation techniques, demonstrates improved consistency, adaptability, and reduced reliance on handcrafted ethical rewards. This method is especially effective in dynamic scenarios where ethical challenges arise unexpectedly, making it well-suited for real-world applications.

[Arxiv](https://arxiv.org/abs/2503.05724)