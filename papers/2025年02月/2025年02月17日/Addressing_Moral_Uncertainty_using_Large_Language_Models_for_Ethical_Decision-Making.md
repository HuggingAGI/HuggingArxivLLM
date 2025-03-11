# 利用大型语言模型应对道德不确定性在道德决策中的应用

发布时间：2025年02月17日

`Agent` `伦理学` `人工智能伦理`

> Addressing Moral Uncertainty using Large Language Models for Ethical Decision-Making

# 摘要

> 我们提出了一种创新的伦理决策框架，通过任务无关的伦理层对预训练的强化学习（RL）模型进行优化。在初始训练后，RL模型进入伦理微调阶段，此时原本需要的人类反馈被大型语言模型（LLM）生成的反馈取代。该LLM基于功利主义、义务论、美德论、社会正义和关怀伦理五大道德原则，在决策过程中为推荐行为分配信念值。伦理层通过信念Jensen-Shannon散度和Dempster-Shafer理论，将多个LLM衍生道德视角的信念分数聚合为概率分数，这些分数不仅作为塑造奖励，还引导代理做出符合平衡伦理框架的选择。这一集成学习框架使RL代理在复杂环境中能够应对道德不确定性，并在多种任务中做出道德上合理的选择。我们的方法在不同LLM变体上进行了测试，并与其它信念聚合技术进行了对比，结果显示该方法在一致性、适应性和减少对人工设计伦理奖励的依赖方面均有显著提升。这种方法尤其适用于动态场景，在这些场景中伦理挑战可能意外出现，因此非常适合应用于实际场景。

> We present an ethical decision-making framework that refines a pre-trained reinforcement learning (RL) model using a task-agnostic ethical layer. Following initial training, the RL model undergoes ethical fine-tuning, where human feedback is replaced by feedback generated from a large language model (LLM). The LLM embodies consequentialist, deontological, virtue, social justice, and care ethics as moral principles to assign belief values to recommended actions during ethical decision-making. An ethical layer aggregates belief scores from multiple LLM-derived moral perspectives using Belief Jensen-Shannon Divergence and Dempster-Shafer Theory into probability scores that also serve as the shaping reward, steering the agent toward choices that align with a balanced ethical framework. This integrated learning framework helps the RL agent navigate moral uncertainty in complex environments and enables it to make morally sound decisions across diverse tasks. Our approach, tested across different LLM variants and compared with other belief aggregation techniques, demonstrates improved consistency, adaptability, and reduced reliance on handcrafted ethical rewards. This method is especially effective in dynamic scenarios where ethical challenges arise unexpectedly, making it well-suited for real-world applications.

[Arxiv](https://arxiv.org/abs/2503.05724)