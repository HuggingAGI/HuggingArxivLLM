# 机器人蛇会像电子羊一样做梦吗？探索架构归纳偏差对幻觉的影响

发布时间：2024年10月22日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）的架构变化如何影响幻觉（即生成虚假或误导性信息）的倾向。研究重点是模型架构的归纳偏差对幻觉的影响，属于对LLM内部机制和理论的研究，因此归类为LLM理论。` `人工智能`

> Do Robot Snakes Dream like Electric Sheep? Investigating the Effects of Architectural Inductive Biases on Hallucination

# 摘要

> 大型语言模型（LLMs）在日常生活中的崛起主要得益于其强大的生成能力，但使用它们也伴随着风险和成本。一方面，LLMs容易产生虚假或误导性信息，即“幻觉”，这削弱了其可靠性。另一方面，传统基于自注意力的LLMs面临计算限制，促使人们探索新的替代方案，如循环模型，以突破这些瓶颈。然而，很少有人同时关注这两个问题。架构的变化是否会加剧或缓解幻觉问题？它们是否会影响幻觉的发生方式和位置？通过深入研究，我们探讨了基于架构的归纳偏差如何影响幻觉的倾向。尽管幻觉是普遍现象，但其发生频率和类型因模型架构而异。这些发现表明，我们需要更全面地理解这两个问题，并设计更通用的技术来应对幻觉。

> The growth in prominence of large language models (LLMs) in everyday life can be largely attributed to their generative abilities, yet some of this is also owed to the risks and costs associated with their use. On one front is their tendency to \textit{hallucinate} false or misleading information, limiting their reliability. On another is the increasing focus on the computational limitations associated with traditional self-attention based LLMs, which has brought about new alternatives, in particular recurrent models, meant to overcome them. Yet it remains uncommon to consider these two concerns simultaneously. Do changes in architecture exacerbate/alleviate existing concerns about hallucinations? Do they affect how and where they occur? Through an extensive evaluation, we study how these architecture-based inductive biases affect the propensity to hallucinate. While hallucination remains a general phenomenon not limited to specific architectures, the situations in which they occur and the ease with which specific types of hallucinations can be induced can significantly differ based on the model architecture. These findings highlight the need for better understanding both these problems in conjunction with each other, as well as consider how to design more universal techniques for handling hallucinations.

[Arxiv](https://arxiv.org/abs/2410.17477)