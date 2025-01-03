# 大型语言模型在长文本中依然存在偏见

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在长文本生成任务中的公平性问题，并提出了一种新的测试方法（LTF-TEST）和微调方法（FT-REGARD）来评估和缓解模型中的偏见。研究内容涉及对LLMs的理论分析、偏见模式的识别以及改进方法的提出，属于对LLMs的理论研究和改进，因此归类为LLM理论。` `公平性评估`

> Large Language Models Still Exhibit Bias in Long Text

# 摘要

> 现有的LLMs公平性基准主要针对简单任务（如选择题），忽略了长文本生成等复杂场景中的潜在偏见。为此，我们推出了长文本公平性测试（LTF-TEST），通过论文式提示评估LLMs的偏见。LTF-TEST涵盖14个主题和10个人口统计轴（如性别、种族），生成11,948个样本。通过分析模型响应及其推理，LTF-TEST揭示了简单响应中难以捕捉的微妙偏见。在对GPT-4o和LLaMa3等五个最新LLMs的评估中，我们发现了两种主要偏见模式：一是模型响应中频繁偏向某些群体；二是对弱势群体过度敏感，提供过度保护性响应，而忽视其他群体。为缓解这些偏见，我们提出了FT-REGARD，一种将偏见提示与中性响应配对的微调方法。FT-REGARD将性别偏见降低了34.6%，并在BBQ基准上提升了1.4个百分点的性能，为长文本生成任务中的偏见问题提供了有效解决方案。

> Existing fairness benchmarks for large language models (LLMs) primarily focus on simple tasks, such as multiple-choice questions, overlooking biases that may arise in more complex scenarios like long-text generation. To address this gap, we introduce the Long Text Fairness Test (LTF-TEST), a framework that evaluates biases in LLMs through essay-style prompts. LTF-TEST covers 14 topics and 10 demographic axes, including gender and race, resulting in 11,948 samples. By assessing both model responses and the reasoning behind them, LTF-TEST uncovers subtle biases that are difficult to detect in simple responses. In our evaluation of five recent LLMs, including GPT-4o and LLaMa3, we identify two key patterns of bias. First, these models frequently favor certain demographic groups in their responses. Second, they show excessive sensitivity toward traditionally disadvantaged groups, often providing overly protective responses while neglecting others. To mitigate these biases, we propose FT-REGARD, a finetuning approach that pairs biased prompts with neutral responses. FT-REGARD reduces gender bias by 34.6% and improves performance by 1.4 percentage points on the BBQ benchmark, offering a promising approach to addressing biases in long-text generation tasks.

[Arxiv](https://arxiv.org/abs/2410.17519)