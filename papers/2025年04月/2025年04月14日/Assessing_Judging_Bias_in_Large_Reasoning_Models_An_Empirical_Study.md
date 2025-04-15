# 大型推理模型的判断偏差评估：实证研究

发布时间：2025年04月14日

`LLM应用` `AI评估` `质量控制`

> Assessing Judging Bias in Large Reasoning Models: An Empirical Study

# 摘要

> 大型推理模型（LRMs）如 DeepSeek-R1 和 OpenAI-o1 展现出了卓越的推理能力，这引发了关于它们在作为大型语言模型（LLM）裁判时的偏见问题。我们提供了一个全面的基准测试，比较了 LLMs 和 LRMs 在主观偏好对齐数据集和客观事实数据集中的裁判偏见。通过对随大流偏见、权威偏见、位置偏见和分心偏见的调查，我们发现了四个关键发现：(1) 尽管 LRMs 具备先进的推理能力，但它们仍然容易受到上述偏见的影响；(2) 与 LLMs 相比，LRMs 在与事实相关的数据集上表现出了更好的鲁棒性；(3) LRMs 显示出显著的位置偏见，更倾向于选择较后出现的选项；(4) 我们发现了一种新型的“表面反思偏见”，其中模仿推理的短语（例如，“等等，让我想想...”）对模型的判断产生了显著影响。为了应对这些偏见，我们设计并评估了三种缓解策略：定制化系统提示，可将偏好对齐数据集中的裁判偏见降低高达 19%，并在事实相关数据集中降低 14%；在上下文学习中，偏好任务的改进高达 27%，但在事实任务中表现不一致；以及自我反思机制，在偏好数据集中可将偏见降低 10%，在事实相关数据集中降低 16%，其中自我反思对 LRMs 尤其有效。我们的研究为开发更可靠的 LLM 作为裁判框架提供了重要见解，特别是在 LRMs 日益被部署为自动裁判的情况下。

> Large Reasoning Models (LRMs) like DeepSeek-R1 and OpenAI-o1 have demonstrated remarkable reasoning capabilities, raising important questions about their biases in LLM-as-a-judge settings. We present a comprehensive benchmark comparing judging biases between LLMs and LRMs across both subjective preference-alignment datasets and objective fact-based datasets. Through investigation of bandwagon, authority, position, and distraction biases, we uncover four key findings: (1) despite their advanced reasoning capabilities, LRMs remain susceptible to the above biases; (2) LRMs demonstrate better robustness than LLMs specifically on fact-related datasets; (3) LRMs exhibit notable position bias, preferring options in later positions; and (4) we identify a novel "superficial reflection bias" where phrases mimicking reasoning (e.g., "wait, let me think...") significantly influence model judgments. To address these biases, we design and evaluate three mitigation strategies: specialized system prompts that reduce judging biases by up to 19\% in preference alignment datasets and 14\% in fact-related datasets, in-context learning that provides up to 27\% improvement on preference tasks but shows inconsistent results on factual tasks, and a self-reflection mechanism that reduces biases by up to 10\% in preference datasets and 16\% in fact-related datasets, with self-reflection proving particularly effective for LRMs. Our work provides crucial insights for developing more reliable LLM-as-a-Judge frameworks, especially as LRMs become increasingly deployed as automated judges.

[Arxiv](https://arxiv.org/abs/2504.09946)