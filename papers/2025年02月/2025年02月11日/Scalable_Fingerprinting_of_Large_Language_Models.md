# 可扩展的大型语言模型指纹识别

发布时间：2025年02月11日

`LLM理论` `人工智能` `模型安全`

> Scalable Fingerprinting of Large Language Models

# 摘要

> 模型指纹识别已成为模型所有者在API访问权限下识别其共享模型的强大工具。然而，为了降低误判率、防止指纹泄露并防御试图规避检测的模型用户联盟，我们认为{\em 可扩展性}至关重要，即增加可以嵌入模型的指纹数量。因此，我们将可扩展性视为指纹识别方案的关键要求。我们在远超以往研究规模的范围内实验了指纹设计，并引入了一种新方法，称为Perinucleus采样，以生成可扩展、持久且无害的指纹。我们证明，该方案可以在Llama-3.1-8B模型中添加24,576个指纹——比现有方案多两个数量级——而不会降低模型的效用。我们的嵌入指纹即使在标准后训练数据上的监督微调后仍然存在。我们进一步探讨了指纹识别的安全风险，并从理论和实证上展示了像我们这样的可扩展指纹识别方案如何缓解这些风险。

> Model fingerprinting has emerged as a powerful tool for model owners to identify their shared model given API access. However, to lower false discovery rate, fight fingerprint leakage, and defend against coalitions of model users attempting to bypass detection, we argue that {\em scalability} is critical, i.e., scaling up the number of fingerprints one can embed into a model. Hence, we pose scalability as a crucial requirement for fingerprinting schemes. We experiment with fingerprint design at a scale significantly larger than previously considered, and introduce a new method, dubbed Perinucleus sampling, to generate scalable, persistent, and harmless fingerprints. We demonstrate that this scheme can add 24,576 fingerprints to a Llama-3.1-8B model -- two orders of magnitude more than existing schemes -- without degrading the model's utility. Our inserted fingerprints persist even after supervised fine-tuning on standard post-training data. We further address security risks for fingerprinting, and theoretically and empirically show how a scalable fingerprinting scheme like ours can mitigate these risks.

[Arxiv](https://arxiv.org/abs/2502.07760)