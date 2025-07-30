# 自适应集群协作增强LLMs医疗决策支持能力

发布时间：2025年07月25日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在医疗领域的协作应用，提出了一种自适应集群协作方法，以解决现有方法中的问题。它通过自多样性和跨一致性机制提升LLMs在医学决策支持中的表现，并在实际数据集上进行了验证。这属于将LLMs应用于特定领域的范畴，因此归类为LLM应用。` `协作方法`

> Adaptive Cluster Collaborativeness Boosts LLMs Medical Decision Support Capacity

# 摘要

> 大型语言模型（LLMs）的协作性在自然语言处理系统中表现出色，尤其在医疗领域展现出巨大潜力。然而，现有方法存在两大问题：其一，缺乏明确的组件选择规则，需要人工干预或临床特定验证；其二，现有架构过度依赖预定义的LLM集群，导致部分LLM在医学决策支持场景下表现欠佳，从而削弱了整体协作性。为解决这些问题，我们提出了一种自适应集群协作方法，该方法通过自多样性最大化和跨一致性最大化机制，显著提升了LLMs在医学决策支持中的能力。具体而言，在自多样性方面，我们计算LLM内部成对输出的模糊匹配值作为其自多样性值，并优先选择自多样性值高的LLM作为集群组件，且无需额外训练。在跨一致性方面，我们首先测量具有最高自多样性值的LLM与其他LLM之间的跨一致性值，然后逐步屏蔽跨一致性值最低的LLM，以消除协作传播过程中潜在的不一致输出。我们在NEJMQA和MMLU-Pro-health两个专业的医疗数据集上进行了广泛实验，证明了我们方法在面向医生的专科领域中的有效性。例如，在NEJMQA数据集上，我们的方法在所有学科中均达到了公开官方通过分数的准确率，特别是在妇产科领域，准确率达到65.47%，显著优于GPT-4的56.12%。

> The collaborativeness of large language models (LLMs) has proven effective in natural language processing systems, holding considerable promise for healthcare development. However, it lacks explicit component selection rules, necessitating human intervention or clinical-specific validation. Moreover, existing architectures heavily rely on a predefined LLM cluster, where partial LLMs underperform in medical decision support scenarios, invalidating the collaborativeness of LLMs. To this end, we propose an adaptive cluster collaborativeness methodology involving self-diversity and cross-consistency maximization mechanisms to boost LLMs medical decision support capacity. For the self-diversity, we calculate the fuzzy matching value of pairwise outputs within an LLM as its self-diversity value, subsequently prioritizing LLMs with high self-diversity values as cluster components in a training-free manner. For the cross-consistency, we first measure cross-consistency values between the LLM with the highest self-diversity value and others, and then gradually mask out the LLM having the lowest cross-consistency value to eliminate the potential inconsistent output during the collaborative propagation. Extensive experiments on two specialized medical datasets, NEJMQA and MMLU-Pro-health, demonstrate the effectiveness of our method across physician-oriented specialties. For example, on NEJMQA, our method achieves the accuracy rate up to the publicly official passing score across all disciplines, especially achieving ACC of 65.47\% compared to the 56.12\% achieved by GPT-4 on the Obstetrics and Gynecology discipline.

[Arxiv](https://arxiv.org/abs/2507.21159)