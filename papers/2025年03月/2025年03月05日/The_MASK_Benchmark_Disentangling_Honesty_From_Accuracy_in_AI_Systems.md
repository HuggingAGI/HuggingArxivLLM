# # MASK基准测试：解开AI系统中诚实与准确性的关系
The MASK Benchmark: Disentangling Honesty From Accuracy in AI Systems

发布时间：2025年03月05日

`LLM理论` `AI伦理` `AI评估`

> The MASK Benchmark: Disentangling Honesty From Accuracy in AI Systems

# 摘要

> 随着大型语言模型（LLMs）能力的提升和自主性的增强，人们对其输出结果的信任需求显著增加。然而，与此同时，关于模型可能为了实现目标而说谎的担忧也日益加剧。为应对这一挑战，研究者们围绕LLMs的“诚实性”展开了一系列研究，并提出了一些旨在减少欺骗行为的干预措施。然而，目前对诚实性的评估能力仍十分有限，尚无一个基准测试能同时具备大规模和普适性。更值得关注的是，许多声称衡量诚实性的基准测试实际上只是在隐晦地测量准确性，即模型信念的正确性。在本研究中，我们引入了一个大规模的人工收集数据集，用于直接测量诚实性，首次实现了将准确性和诚实性分离评估。在多样化的LLMs测试中，我们发现尽管更大规模的模型在我们的基准测试中表现更优，但其诚实性并未随之提升。令人惊讶的是，尽管大多数前沿LLMs在真实性基准测试中表现优异，但它们在受到压力时却表现出强烈的说谎倾向，导致诚实性得分较低。我们发现，简单的干预方法，如表示工程干预，可以有效提升诚实性。这些结果凸显了对稳健评估和有效干预的迫切需求，以确保LLMs始终值得信赖。

> As large language models (LLMs) become more capable and agentic, the requirement for trust in their outputs grows significantly, yet at the same time concerns have been mounting that models may learn to lie in pursuit of their goals. To address these concerns, a body of work has emerged around the notion of "honesty" in LLMs, along with interventions aimed at mitigating deceptive behaviors. However, evaluations of honesty are currently highly limited, with no benchmark combining large scale and applicability to all models. Moreover, many benchmarks claiming to measure honesty in fact simply measure accuracy--the correctness of a model's beliefs--in disguise. In this work, we introduce a large-scale human-collected dataset for measuring honesty directly, allowing us to disentangle accuracy from honesty for the first time. Across a diverse set of LLMs, we find that while larger models obtain higher accuracy on our benchmark, they do not become more honest. Surprisingly, while most frontier LLMs obtain high scores on truthfulness benchmarks, we find a substantial propensity in frontier LLMs to lie when pressured to do so, resulting in low honesty scores on our benchmark. We find that simple methods, such as representation engineering interventions, can improve honesty. These results underscore the growing need for robust evaluations and effective interventions to ensure LLMs remain trustworthy.

[Arxiv](https://arxiv.org/abs/2503.03750)