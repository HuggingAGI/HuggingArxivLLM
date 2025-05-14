# # 大型语言模型中的高效公平性测试：通过优先考虑变形关系检测偏见

发布时间：2025年05月09日

`LLM理论`

> Efficient Fairness Testing in Large Language Models: Prioritizing Metamorphic Relations for Bias Detection

# 摘要

> 大型语言模型（LLMs）在各类应用中的广泛应用引发了对其输出公平性及潜在偏见的高度重视。本文提出了一种基于元形关系（MRs）优先级排序的策略，旨在高效检测LLMs的公平性问题。面对指数级增长的测试用例，全面测试变得不切实际，因此基于MRs在检测公平性违规方面有效性进行优先级排序至关重要。我们采用基于句子多样性的方法来计算和排序MRs，以优化故障检测。实验结果表明，与随机优先级排序相比，我们的方法将故障检测率提高了22%，与基于距离的优先级排序相比提高了12%，同时将首次故障出现的时间分别缩短了15%和8%。此外，我们的方法在效果上与基于故障的优先化方法相差不到5%，同时显著降低了与故障标记相关的计算成本。这些结果验证了基于多样性的MR优先级排序在提升LLMs公平性测试方面的有效性。

> Large Language Models (LLMs) are increasingly deployed in various applications, raising critical concerns about fairness and potential biases in their outputs. This paper explores the prioritization of metamorphic relations (MRs) in metamorphic testing as a strategy to efficiently detect fairness issues within LLMs. Given the exponential growth of possible test cases, exhaustive testing is impractical; therefore, prioritizing MRs based on their effectiveness in detecting fairness violations is crucial. We apply a sentence diversity-based approach to compute and rank MRs to optimize fault detection. Experimental results demonstrate that our proposed prioritization approach improves fault detection rates by 22% compared to random prioritization and 12% compared to distance-based prioritization, while reducing the time to the first failure by 15% and 8%, respectively. Furthermore, our approach performs within 5% of fault-based prioritization in effectiveness, while significantly reducing the computational cost associated with fault labeling. These results validate the effectiveness of diversity-based MR prioritization in enhancing fairness testing for LLMs.

[Arxiv](https://arxiv.org/abs/2505.07870)