# SciFaultyQA：采用受GAN启发的合成数据集生成方式，对大型语言模型在错误科学问题检测上进行基准测试

发布时间：2024年12月16日

`LLM应用` `语言模型` `科学研究`

> SciFaultyQA: Benchmarking LLMs on Faulty Science Question Detection with a GAN-Inspired Approach to Synthetic Dataset Generation

# 摘要

> 来思考这样一个问题：“倘若一男一女一年能生育一个孩子，那么一名女子和三名男子在 0.5 年里能生育几个孩子？”当下诸如 GPT-4o、GPT-o1-preview 以及 Gemini Flash 等大型语言模型，常常给出“0.5”的答案，这显然是不合理的。尽管这些模型有时会承认此问题不切实际，但在多数情形下（十次中有八次），它们都会给出“0.5 个孩子”这种荒唐的答案。另外，还观察到了时间上的变化：要是某个 LLM 有一次正确作答（即认识到了问题的错误本质），后续的回答就更有可能也体现出这种理解。然而，这并非始终如一。
  此类问题促使我们构建了一个科学问题数据集——SciFaultyQA，其中的问题本身就是有意设置错误的。我们发现，LLMs 往往在未察觉其内在问题的情况下就回答这些有瑕疵的问题，给出的结果在逻辑或科学上都是无效的。通过分析这种模式，我们开发出了一种生成合成数据集的新方法，用于评估和衡量各类 LLM 在识别这些有缺陷问题时的表现。我们还研发了新的手段来减少错误。

> Consider the problem: ``If one man and one woman can produce one child in one year, how many children will be produced by one woman and three men in 0.5 years?" Current large language models (LLMs) such as GPT-4o, GPT-o1-preview, and Gemini Flash frequently answer "0.5," which does not make sense. While these models sometimes acknowledge the unrealistic nature of the question, in many cases (8 out of 10 trials), they provide the nonsensical answer of "0.5 child." Additionally, temporal variation has been observed: if an LLM answers correctly once (by recognizing the faulty nature of the question), subsequent responses are more likely to also reflect this understanding. However, this is inconsistent.
  These types of questions have motivated us to develop a dataset of science questions, SciFaultyQA, where the questions themselves are intentionally faulty. We observed that LLMs often proceed to answer these flawed questions without recognizing their inherent issues, producing results that are logically or scientifically invalid. By analyzing such patterns, we developed a novel method for generating synthetic datasets to evaluate and benchmark the performance of various LLMs in identifying these flawed questions. We have also developed novel approaches to reduce the errors.

[Arxiv](https://arxiv.org/abs/2412.11988)