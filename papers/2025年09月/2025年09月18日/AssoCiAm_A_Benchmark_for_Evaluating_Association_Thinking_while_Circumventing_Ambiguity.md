# AssoCiAm：规避歧义下的关联思维评估基准

发布时间：2025年09月18日

`LLM应用` `基础理论`

> AssoCiAm: A Benchmark for Evaluating Association Thinking while Circumventing Ambiguity

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展备受瞩目，为实现人工通用智能（AGI）开辟了充满希望的道路。在AGI所需的核心能力中，创造力已成为MLLMs的关键特质，而联想正是创造力的基石。联想能力体现了模型的创造性思维水平，因此对其进行评估和深入理解意义重大。尽管已有多个框架用于评估联想能力，但它们常常忽略了联想任务中与生俱来的模糊性——这种模糊性源于联想的发散本质，进而降低了评估的可信度。为解决这一难题，我们将模糊性拆解为内部模糊性和外部模糊性两类，并提出了AssoCiAm基准——它通过混合计算方法规避模糊性，专门用于评估联想能力。接着，我们在MLLMs上开展了广泛实验，结果表明认知与联想之间存在显著的正相关性。此外，我们还发现评估过程中的模糊性会使MLLMs的行为更趋随机化。最后，我们验证了所提方法在确保评估更准确、更可靠方面的有效性。相关数据和代码可参见项目页面。

> Recent advancements in multimodal large language models (MLLMs) have garnered significant attention, offering a promising pathway toward artificial general intelligence (AGI). Among the essential capabilities required for AGI, creativity has emerged as a critical trait for MLLMs, with association serving as its foundation. Association reflects a model' s ability to think creatively, making it vital to evaluate and understand. While several frameworks have been proposed to assess associative ability, they often overlook the inherent ambiguity in association tasks, which arises from the divergent nature of associations and undermines the reliability of evaluations. To address this issue, we decompose ambiguity into two types-internal ambiguity and external ambiguity-and introduce AssoCiAm, a benchmark designed to evaluate associative ability while circumventing the ambiguity through a hybrid computational method. We then conduct extensive experiments on MLLMs, revealing a strong positive correlation between cognition and association. Additionally, we observe that the presence of ambiguity in the evaluation process causes MLLMs' behavior to become more random-like. Finally, we validate the effectiveness of our method in ensuring more accurate and reliable evaluations. See Project Page for the data and codes.

[Arxiv](https://arxiv.org/abs/2509.14171)