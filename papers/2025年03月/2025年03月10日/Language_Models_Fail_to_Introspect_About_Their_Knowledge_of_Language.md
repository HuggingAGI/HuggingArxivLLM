# # 语言模型无法自省它们的语言知识
语言模型无法自省它们的语言知识。

发布时间：2025年03月10日

`LLM理论

理由：这篇论文探讨了大型语言模型的自我反思能力，分析了模型在语法知识和单词预测方面的内部语言知识，提出了新的反思衡量标准，并评估了模型对元语言提示的反应是否真实反映了其内部知识。这些内容都涉及对LLM内部机制和能力的理论研究，因此归类为LLM理论。` `人工智能`

> Language Models Fail to Introspect About Their Knowledge of Language

# 摘要

> 近期研究关注大型语言模型（LLMs）是否能够自我反思其内部状态。这种能力不仅提升LLMs的可解释性，也验证了使用标准反思方法评估模型语法知识的可行性（例如，通过提问“这个句子是否合乎语法？”）。我们系统性地研究了21个开源LLMs在语法知识和单词预测这两个具有理论意义领域的自我反思能力。值得注意的是，这两个领域的模型内部语言知识均可通过直接测量字符串概率获得理论支持。随后，我们评估模型对元语言提示的反应是否真实反映了其内部知识。我们提出了一种新的反思衡量标准：模型在提示后的反应预测其字符串概率的程度，超出另一个具有几乎相同内部知识的模型的预测能力。尽管元语言提示和概率比较均实现了高任务准确性，但我们并未发现LLMs拥有特殊“自我访问”能力的证据。我们的发现使近期关于模型具备自我反思能力的结论复杂化，并为论点增添了新证据，即提示响应不应与模型的语言泛化相混淆。

> There has been recent interest in whether large language models (LLMs) can introspect about their own internal states. Such abilities would make LLMs more interpretable, and also validate the use of standard introspective methods in linguistics to evaluate grammatical knowledge in models (e.g., asking "Is this sentence grammatical?"). We systematically investigate emergent introspection across 21 open-source LLMs, in two domains where introspection is of theoretical interest: grammatical knowledge and word prediction. Crucially, in both domains, a model's internal linguistic knowledge can be theoretically grounded in direct measurements of string probability. We then evaluate whether models' responses to metalinguistic prompts faithfully reflect their internal knowledge. We propose a new measure of introspection: the degree to which a model's prompted responses predict its own string probabilities, beyond what would be predicted by another model with nearly identical internal knowledge. While both metalinguistic prompting and probability comparisons lead to high task accuracy, we do not find evidence that LLMs have privileged "self-access". Our findings complicate recent results suggesting that models can introspect, and add new evidence to the argument that prompted responses should not be conflated with models' linguistic generalizations.

[Arxiv](https://arxiv.org/abs/2503.07513)