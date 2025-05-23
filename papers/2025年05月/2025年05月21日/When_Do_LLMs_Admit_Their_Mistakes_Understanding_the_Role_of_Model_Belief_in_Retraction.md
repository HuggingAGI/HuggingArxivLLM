# 大型语言模型会在什么时候主动承认错误？理解模型信念在撤回中的作用

发布时间：2025年05月21日

`LLM理论

论文摘要探讨了大型语言模型（LLMs）在生成错误答案后是否会承认错误，以及撤回行为的条件和原因。研究深入分析了模型的内部信念、注意力机制以及如何通过监督微调提升撤回性能，属于对模型理论层面的探索。因此，归类为LLM理论。` `人工智能`

> When Do LLMs Admit Their Mistakes? Understanding the Role of Model Belief in Retraction

# 摘要

> 大型语言模型（LLMs）在明知有误的情况下是否会承认错误？本研究将承认先前生成答案中的错误行为定义为“撤回”，并深入探讨LLMs何时以及为何选择撤回。我们构建了特定于模型的数据集，评估模型是否会撤回与其自身知识相矛盾的错误答案。尽管LLMs具备撤回能力，但这种行为并不常见。研究表明，撤回与模型内部信念密切相关：当模型“认为”答案在事实层面正确时，就不会撤回错误答案。转向实验进一步证实，内部信念在因果上影响模型的撤回行为。特别地，当模型对自身答案缺乏信心时，不仅会主动尝试验证答案，还会在自我验证过程中调整注意力行为。最后，我们发现，通过简单的监督微调，模型能够学习更准确的内部信念，从而显著提升撤回性能。代码和数据集可在GitHub仓库https://github.com/ayyyq/llm-retraction中获取。

> Can large language models (LLMs) admit their mistakes when they should know better? In this work, we define the behavior of acknowledging errors in previously generated answers as "retraction" and aim to understand when and why LLMs choose to retract. We first construct model-specific datasets to evaluate whether a model will retract an incorrect answer that contradicts its own parametric knowledge. While LLMs are capable of retraction, they do so only infrequently. We demonstrate that retraction is closely tied to previously identified indicators of models' internal belief: models fail to retract wrong answers that they "believe" to be factually correct. Steering experiments further demonstrate that internal belief causally influences model retraction. In particular, when the model does not believe its answer, this not only encourages the model to attempt to verify the answer, but also alters attention behavior during self-verification. Finally, we demonstrate that simple supervised fine-tuning significantly improves retraction performance by helping the model learn more accurate internal beliefs. Code and datasets are available on https://github.com/ayyyq/llm-retraction.

[Arxiv](https://arxiv.org/abs/2505.16170)