# # KOFFVQA：专为韩语大型视觉-语言模型设计的客观评估自由形式VQA基准

发布时间：2025年03月31日

`LLM应用

理由：这篇论文提出了一种新的基准测试方法（KOFFVQA），用于评估韩语环境下的视觉语言模型（VLMs）。它专注于模型的应用和评估，特别是在特定语言环境中的性能，属于LLM应用的范畴。` `视觉问答` `基准测试`

> KOFFVQA: An Objectively Evaluated Free-form VQA Benchmark for Large Vision-Language Models in the Korean Language

# 摘要

> 大型视觉语言模型（VLMs）的 recent emergence 近期出现催生了多种多样的基准测试用于评估此类模型。尽管如此，我们观察到大多数现有评估方法都存在以下问题：要么要求模型从预设的响应中进行选择，这牺牲了开放性；要么使用判别模型对响应进行评估，导致主观性和不可靠性。此外，我们发现缺乏针对韩语的 VLMs 基准测试，这作为与更常见的英语语言基准测试分开的指标是必要的，因为生成式语言模型的性能可能因语言的不同而显著差异。因此，我们提出了 KOFFVQA，这是一个通用的自由形式视觉问答基准测试，用于韩语环境下的 VLMs 评估。我们的基准测试包含 275 个精心设计的问题，每个问题都配有一张图像和涵盖 VLM 性能 10 个不同方面的评分标准。这些评分标准通过允许判别模型根据预设规则对每个响应进行评分，从而消除了不可靠性问题。通过以客观方式定义评估标准，即使是一个小型开源模型也可以可靠地用于在我们的基准测试上评估模型。除了在我们的基准测试上评估大量现有的 VLMs 之外，我们还实验证明，我们使用预设评分标准进行评估的方法比现有方法可靠得多。我们的评估代码可在 https://github.com/maum-ai/KOFFVQA 获取。

> The recent emergence of Large Vision-Language Models(VLMs) has resulted in a variety of different benchmarks for evaluating such models. Despite this, we observe that most existing evaluation methods suffer from the fact that they either require the model to choose from pre-determined responses, sacrificing open-endedness, or evaluate responses using a judge model, resulting in subjective and unreliable evaluation. In addition, we observe a lack of benchmarks for VLMs in the Korean language, which are necessary as a separate metric from more common English language benchmarks, as the performance of generative language models can differ significantly based on the language being used. Therefore, we present KOFFVQA, a general-purpose free-form visual question answering benchmark in the Korean language for the evaluation of VLMs. Our benchmark consists of 275 carefully crafted questions each paired with an image and grading criteria covering 10 different aspects of VLM performance. The grading criteria eliminate the problem of unreliability by allowing the judge model to grade each response based on a pre-determined set of rules. By defining the evaluation criteria in an objective manner, even a small open-source model can be used to evaluate models on our benchmark reliably. In addition to evaluating a large number of existing VLMs on our benchmark, we also experimentally verify that our method of using pre-existing grading criteria for evaluation is much more reliable than existing methods. Our evaluation code is available at https://github.com/maum-ai/KOFFVQA

[Arxiv](https://arxiv.org/abs/2503.23730)