# 语言模型的推理基础自然语言解释

发布时间：2025年03月14日

`LLM理论`

> Reasoning-Grounded Natural Language Explanations for Language Models

# 摘要

> 我们提出了一种大型语言模型可解释性技术，通过将解释建立在推理过程中，生成忠实的自然语言解释。推理过程的输出可转换为标记序列，作为模型上下文的一部分，并在模型生成最终答案或解释时解码为自然语言。为提升解释的忠实性，我们建议采用一种联合预测-解释方法，其中答案和解释直接从推理序列中推断，彼此独立。通过在多个问题领域中实现答案与解释的高度一致性，我们证明了该技术的可行性，发现语言模型常将推理序列中的部分决策复制到最终答案或解释中。此外，我们还表明，推理方法的引入可有效提升答案质量。

> We propose a large language model explainability technique for obtaining faithful natural language explanations by grounding the explanations in a reasoning process. When converted to a sequence of tokens, the outputs of the reasoning process can become part of the model context and later be decoded to natural language as the model produces either the final answer or the explanation. To improve the faithfulness of the explanations, we propose to use a joint predict-explain approach, in which the answers and explanations are inferred directly from the reasoning sequence, without the explanations being dependent on the answers and vice versa. We demonstrate the plausibility of the proposed technique by achieving a high alignment between answers and explanations in several problem domains, observing that language models often simply copy the partial decisions from the reasoning sequence into the final answers or explanations. Furthermore, we show that the proposed use of reasoning can also improve the quality of the answers.

[Arxiv](https://arxiv.org/abs/2503.11248)