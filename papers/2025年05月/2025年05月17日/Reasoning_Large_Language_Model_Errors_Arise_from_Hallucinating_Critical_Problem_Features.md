# 大型语言模型推理错误源于虚构关键问题特征

发布时间：2025年05月17日

`LLM应用` `人工智能`

> Reasoning Large Language Model Errors Arise from Hallucinating Critical Problem Features

# 摘要

> 大型语言模型通过强化学习训练的链式思维（CoT）策略，在推理任务上取得了显著进展；然而，这些“推理大型语言模型”（RLLMs）仍然存在推理缺陷。理解其失效模式的频率和原因，对于用户和开发者都至关重要。我们测试了o1-mini、o3-mini、DeepSeek-R1、Claude 3.7 Sonnet、Gemini 2.5 Pro Preview和Grok 3 Mini Beta在图着色这一变复杂度约束满足逻辑问题上的表现。通过错误率比较和CoT/解释文本分析，我们发现RLLMs容易虚构提示中未明确说明的图边。这一现象在多个问题复杂度水平和语义框架下持续存在，似乎占每个测试模型错误答案的相当一部分，对某些模型来说甚至占绝大多数。我们的研究结果表明，RLLMs可能在问题细节的表示上存在更广泛的问题。为此，我们提出了一些建议的设计选择，以缓解这一弱点。

> Large language models have recently made great strides in reasoning task performance through chain-of-thought (CoT) strategies trained via reinforcement learning; however, these "reasoning large language models" (RLLMs) remain imperfect reasoners, and understanding the frequencies and causes of their failure modes is important for both users and developers. We test o1-mini, o3-mini, DeepSeek-R1, Claude 3.7 Sonnet, Gemini 2.5 Pro Preview, and Grok 3 Mini Beta on graph coloring as a variable-complexity constraint-satisfaction logic problem, and find evidence from both error rate comparisons and CoT/explanation text analysis that RLLMs are prone to hallucinate edges not specified in the prompt's description of the graph. This phenomenon persists across multiple problem complexity levels and semantic frames, and it appears to account for a significant fraction of the incorrect answers from every tested model, and the vast majority of them for some models. Our results indicate that RLLMs may possess broader issues with misrepresentation of problem specifics, and we offer suggestions for design choices to mitigate this weakness.

[Arxiv](https://arxiv.org/abs/2505.12151)