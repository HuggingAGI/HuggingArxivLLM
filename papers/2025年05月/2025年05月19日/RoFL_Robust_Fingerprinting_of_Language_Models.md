# # RoFL: 语言模型的稳健指纹识别
Robust Fingerprinting of Language Models 是一种用于语言模型指纹识别的稳健方法，旨在提升模型指纹识别的可靠性和准确性。

发布时间：2025年05月19日

`LLM应用` `法律合规` `网络安全`

> RoFL: Robust Fingerprinting of Language Models

# 摘要

> AI 开发者正以多种许可证发布大型语言模型（LLMs），许多许可证限制了模型的使用方式。这引出了如何识别许可证违规的问题，特别是如何确定某个 API 或产品使用了特定的 LLM。我们提出了一种新方法，通过“指纹”实现模型识别：这些是开发者模型独有的统计模式，能够抵御常见修改。我们的方法可在黑盒环境下通过有限查询识别模型，适用于仅通过 API 或产品访问的模型。这些指纹是非侵入式的，无需在训练中修改模型，因此不会影响模型质量。实证研究表明，我们的方法对模型或推理设置的常见更改具有高度鲁棒性。实验显示，它显著优于包括侵入式方法在内的先前技术。

> AI developers are releasing large language models (LLMs) under a variety of different licenses. Many of these licenses restrict the ways in which the models or their outputs may be used. This raises the question how license violations may be recognized. In particular, how can we identify that an API or product uses (an adapted version of) a particular LLM? We present a new method that enable model developers to perform such identification via fingerprints: statistical patterns that are unique to the developer's model and robust to common alterations of that model. Our method permits model identification in a black-box setting using a limited number of queries, enabling identification of models that can only be accessed via an API or product. The fingerprints are non-invasive: our method does not require any changes to the model during training, hence by design, it does not impact model quality. Empirically, we find our method provides a high degree of robustness to common changes in the model or inference settings. In our experiments, it substantially outperforms prior art, including invasive methods that explicitly train watermarks into the model.

[Arxiv](https://arxiv.org/abs/2505.12682)