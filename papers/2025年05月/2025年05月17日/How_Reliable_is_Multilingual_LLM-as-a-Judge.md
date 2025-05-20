# 多语言大语言模型充当裁判，可靠性几何？

发布时间：2025年05月17日

`LLM应用

理由：这篇论文探讨了基于大语言模型的评估策略在多语言环境下的应用及其可靠性问题，属于大语言模型的实际应用研究。` `多语言评估`

> How Reliable is Multilingual LLM-as-a-Judge?

# 摘要

> 基于大语言模型的评估策略（LLM-as-a-Judge）作为一种流行的评估方法，通过先进的大型语言模型根据人类指令对生成结果进行评估。虽然这些模型为人工标注提供了一个有前景的替代方案，但它们在多语言评估中的可靠性仍存在疑问。为了填补这一研究空白，我们对多语言环境下的LLM-as-a-Judge进行了全面分析。具体而言，我们评估了来自不同模型家族的五种模型在涉及25种语言的五种多样化任务中的表现。研究发现，大型语言模型在不同语言间难以保持一致的评估结果，平均Fleiss' Kappa值约为0.3，某些模型的表现甚至更差。为了探究不一致性的原因，我们分析了各种影响因素。观察发现，不同语言间的一致性存在显著差异，特别是在低资源语言中表现尤为不佳。此外，我们还发现，无论是基于多语言数据的训练，还是增加模型规模，都无法直接提高评估一致性。这些发现表明，大型语言模型目前尚无法可靠地用于多语言预测评估。最后，我们提出了一种集成策略，以提升多语言评估在实际应用中的一致性。

> LLM-as-a-Judge has emerged as a popular evaluation strategy, where advanced large language models assess generation results in alignment with human instructions. While these models serve as a promising alternative to human annotators, their reliability in multilingual evaluation remains uncertain. To bridge this gap, we conduct a comprehensive analysis of multilingual LLM-as-a-Judge. Specifically, we evaluate five models from different model families across five diverse tasks involving 25 languages. Our findings reveal that LLMs struggle to achieve consistent judgment results across languages, with an average Fleiss' Kappa of approximately 0.3, and some models performing even worse. To investigate the cause of inconsistency, we analyze various influencing factors. We observe that consistency varies significantly across languages, with particularly poor performance in low-resource languages. Additionally, we find that neither training on multilingual data nor increasing model scale directly improves judgment consistency. These findings suggest that LLMs are not yet reliable for evaluating multilingual predictions. We finally propose an ensemble strategy which improves the consistency of the multilingual judge in real-world applications.

[Arxiv](https://arxiv.org/abs/2505.12201)