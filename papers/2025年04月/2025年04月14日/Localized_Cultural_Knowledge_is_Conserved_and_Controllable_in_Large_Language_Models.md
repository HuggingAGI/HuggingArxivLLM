# 大型语言模型中本地化的文化知识不仅能够得到有效保留，同时还能实现可控性。

发布时间：2025年04月14日

`LLM应用` `文化本地化`

> Localized Cultural Knowledge is Conserved and Controllable in Large Language Models

# 摘要

> 就像人类在学习新语言时会受到母语的影响一样，LLMs在生成非英语内容时，往往会倾向于以英语为中心的回应方式。然而，本地文化信息仍然保留在模型中，并且可以随时被激活以实现文化定制。我们证明，明确在提示中提供文化背景，可以显著提高模型生成文化本地化回应的能力。我们将模型在有无明确文化背景提示下的性能差异称为显式-隐式本地化差距，这表明虽然文化知识存在于LLMs中，但如果未明确提供文化背景，这些知识可能不会在多语言交互中自然呈现。尽管明确提示带来了益处，但回答的多样性却有所下降，并倾向于刻板印象。我们发现了一种在所有非英语语言中都存在的显式文化定制向量，它能够引导LLMs从合成的英语文化世界模型转向每种非英语文化世界。经过引导后的回应保留了隐式提示的多样性，并减少了刻板印象，从而极大地提高了定制潜力。显式文化定制对理解LLMs中替代文化世界模型的保守性及其在翻译、文化定制方面的可控实用性具有重要意义，同时通过软控制扩大LLM功能和吸引力的可能性，从而实现将显式转化为隐式。

> Just as humans display language patterns influenced by their native tongue when speaking new languages, LLMs often default to English-centric responses even when generating in other languages. Nevertheless, we observe that local cultural information persists within the models and can be readily activated for cultural customization. We first demonstrate that explicitly providing cultural context in prompts significantly improves the models' ability to generate culturally localized responses. We term the disparity in model performance with versus without explicit cultural context the explicit-implicit localization gap, indicating that while cultural knowledge exists within LLMs, it may not naturally surface in multilingual interactions if cultural context is not explicitly provided. Despite the explicit prompting benefit, however, the answers reduce in diversity and tend toward stereotypes. Second, we identify an explicit cultural customization vector, conserved across all non-English languages we explore, which enables LLMs to be steered from the synthetic English cultural world-model toward each non-English cultural world. Steered responses retain the diversity of implicit prompting and reduce stereotypes to dramatically improve the potential for customization. We discuss the implications of explicit cultural customization for understanding the conservation of alternative cultural world models within LLMs, and their controllable utility for translation, cultural customization, and the possibility of making the explicit implicit through soft control for expanded LLM function and appeal.

[Arxiv](https://arxiv.org/abs/2504.10191)