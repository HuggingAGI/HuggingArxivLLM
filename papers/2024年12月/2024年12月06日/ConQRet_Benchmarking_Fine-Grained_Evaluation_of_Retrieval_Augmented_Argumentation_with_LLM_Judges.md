# ConQRet：以 LLM 评委为基准对检索增强论证展开细粒度评估

发布时间：2024年12月06日

`LLM应用` `计算论证` `争议话题`

> ConQRet: Benchmarking Fine-Grained Evaluation of Retrieval Augmented Argumentation with LLM Judges

# 摘要

> 计算论证，即针对诸如堕胎禁令和疫苗接种这类颇具争议的话题生成答案或总结，在当下两极分化的环境中愈发重要。先进的 LLM 能力有望通过检索增强论证（RAArg）为这类问题给出细致且基于证据的答案，借助现实世界的证据来形成高质量、有依据的论证。然而，评估 RAArg 颇具挑战，因为人工评估成本高，对于复杂主题的冗长复杂答案而言更是困难重重。同时，复用现有的论证数据集已不满足需求，因其缺少冗长复杂的论证以及可能来自具有误导性来源的真实证据，这限制了对检索效果和论证质量的全面评估。为填补这些空缺，我们研究了使用多个细粒度 LLM 评判员的自动评估方法，提供了比传统单分数指标甚至此前报道的人工众包更出色且更具解释性的评估。为验证所提出的技术，我们引入了 ConQRet 这一新基准，其中包含关于争议话题的冗长复杂的人工撰写的论证，基于真实世界的网站，能够对检索效果、论证质量和依据性进行详尽评估。我们在前序数据集和新的 ConQRet 基准上对我们的 LLM 评判员进行了验证。我们提出的 LLM 评判员和 ConQRet 基准能够促进计算论证的快速进步，并能自然地拓展到其他复杂的检索增强生成任务。

> Computational argumentation, which involves generating answers or summaries for controversial topics like abortion bans and vaccination, has become increasingly important in today's polarized environment. Sophisticated LLM capabilities offer the potential to provide nuanced, evidence-based answers to such questions through Retrieval-Augmented Argumentation (RAArg), leveraging real-world evidence for high-quality, grounded arguments. However, evaluating RAArg remains challenging, as human evaluation is costly and difficult for complex, lengthy answers on complicated topics. At the same time, re-using existing argumentation datasets is no longer sufficient, as they lack long, complex arguments and realistic evidence from potentially misleading sources, limiting holistic evaluation of retrieval effectiveness and argument quality. To address these gaps, we investigate automated evaluation methods using multiple fine-grained LLM judges, providing better and more interpretable assessments than traditional single-score metrics and even previously reported human crowdsourcing. To validate the proposed techniques, we introduce ConQRet, a new benchmark featuring long and complex human-authored arguments on debated topics, grounded in real-world websites, allowing an exhaustive evaluation across retrieval effectiveness, argument quality, and groundedness. We validate our LLM Judges on a prior dataset and the new ConQRet benchmark. Our proposed LLM Judges and the ConQRet benchmark can enable rapid progress in computational argumentation and can be naturally extended to other complex retrieval-augmented generation tasks.

[Arxiv](https://arxiv.org/abs/2412.05206)