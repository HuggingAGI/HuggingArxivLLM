# 义务论关键词偏差：情态表达对语言模型规范性判断的影响

发布时间：2025年06月01日

`LLM应用`

> Deontological Keyword Bias: The Impact of Modal Expressions on Normative Judgments of Language Models

# 摘要

> 大型语言模型 (LLMs) 日益深入地参与道德与伦理推理，但这类推理的判断标准往往模糊不清，即使是人类也难以明确。尽管 LLM 对齐研究涉及诸多领域，但 LLM 如何判断义务仍是一个关键且尚未充分探索的领域。本研究发现，当提示中加入模态表达（如“必须”或“应该”）时，LLMs 倾向于将非义务情境判定为义务，我们将其命名为“义务关键词偏见” (DKB)。研究发现，存在模态表达时，LLMs 会将超过 90% 的常识情境判定为义务。这种倾向在不同 LLM 家族、问题类型和答案格式中均普遍存在。为缓解 DKB，我们提出了一种结合少量示例与推理提示的判断策略。这项研究揭示了模态表达作为语言框架对 LLM 规范性决策的影响，并强调了应对此类偏见以确保判断对齐的重要性。

> Large language models (LLMs) are increasingly engaging in moral and ethical reasoning, where criteria for judgment are often unclear, even for humans. While LLM alignment studies cover many areas, one important yet underexplored area is how LLMs make judgments about obligations. This work reveals a strong tendency in LLMs to judge non-obligatory contexts as obligations when prompts are augmented with modal expressions such as must or ought to. We introduce this phenomenon as Deontological Keyword Bias (DKB). We find that LLMs judge over 90\% of commonsense scenarios as obligations when modal expressions are present. This tendency is consist across various LLM families, question types, and answer formats. To mitigate DKB, we propose a judgment strategy that integrates few-shot examples with reasoning prompts. This study sheds light on how modal expressions, as a form of linguistic framing, influence the normative decisions of LLMs and underscores the importance of addressing such biases to ensure judgment alignment.

[Arxiv](https://arxiv.org/abs/2506.11068)