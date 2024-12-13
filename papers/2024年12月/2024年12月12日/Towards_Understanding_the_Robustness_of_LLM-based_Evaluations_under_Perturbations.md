# 旨在理解扰动下基于 LLM 的评估的稳健性

发布时间：2024年12月12日

`LLM应用` `评估指标`

> Towards Understanding the Robustness of LLM-based Evaluations under Perturbations

# 摘要

> 传统的评估指标，如 BLEU 和 ROUGE，在捕捉生成文本的细微之处时力有不逮，尤其是在没有单一的标准真相时。在本文中，我们探究了大型语言模型（LLMs），特别是谷歌的 Gemini 1，充当总结和基于对话任务中非标准化指标自动评估器的潜力。我们通过多种提示策略开展实验，考察与 SummEval 和 USR 数据集中的人类判断相比，LLMs 作为质量评估器的情况，要求模型生成分数以及给出分数的依据。另外，我们借助使用扰动输入来探索 LLM 评估器的稳健性。我们的发现表明，虽然 LLMs 颇具前景，但其与人类评估者的一致性有限，面对扰动不够稳健，要想单独用作主观指标的可靠评估器，还需要大幅改进。

> Traditional evaluation metrics like BLEU and ROUGE fall short when capturing the nuanced qualities of generated text, particularly when there is no single ground truth. In this paper, we explore the potential of Large Language Models (LLMs), specifically Google Gemini 1, to serve as automatic evaluators for non-standardized metrics in summarization and dialog-based tasks. We conduct experiments across multiple prompting strategies to examine how LLMs fare as quality evaluators when compared with human judgments on the SummEval and USR datasets, asking the model to generate both a score as well as a justification for the score. Furthermore, we explore the robustness of the LLM evaluator by using perturbed inputs. Our findings suggest that while LLMs show promise, their alignment with human evaluators is limited, they are not robust against perturbations and significant improvements are required for their standalone use as reliable evaluators for subjective metrics.

[Arxiv](https://arxiv.org/abs/2412.09269)