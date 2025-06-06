# DRE：一种有效的双精炼方法，融合小型和大型语言模型，应用于开放领域对话评估。

发布时间：2025年06月04日

`LLM应用` `对话评估`

> DRE: An Effective Dual-Refined Method for Integrating Small and Large Language Models in Open-Domain Dialogue Evaluation

# 摘要

> 大型语言模型 (LLMs) 在许多任务上表现出色，但在存在多个有效回答的模糊场景下，往往产生不可靠的结果。相比之下，小型语言模型 (SLMs) 在此类场景中表现得更为稳健，但容易受到误导性或对抗性输入的影响。我们发现，LLMs 在处理反例时表现出色，而 SLMs 则擅长处理正例。为了充分利用它们的互补优势，我们引入了 SLIDE（Small and Large Integrated for Dialogue Evaluation），这是一种通过自适应加权整合 SLMs 和 LLMs 的方法。基于 SLIDE，我们进一步提出了双精炼评估 (DRE) 方法，以提升 SLM-LLM 整合效果：（1）SLM 生成的见解引导 LLM 生成初步评估；（2）SLM 衍生的调整优化 LLM 的评分，从而提高准确性。实验表明，DRE 在现有方法中表现最优，在多种基准测试中与人工判断的契合度更强。这项研究展示了如何通过结合小型和大型模型，打造更可靠的评估工具，尤其适用于对话评估等开放性任务。

> Large Language Models (LLMs) excel at many tasks but struggle with ambiguous scenarios where multiple valid responses exist, often yielding unreliable results. Conversely, Small Language Models (SLMs) demonstrate robustness in such scenarios but are susceptible to misleading or adversarial inputs. We observed that LLMs handle negative examples effectively, while SLMs excel with positive examples. To leverage their complementary strengths, we introduce SLIDE (Small and Large Integrated for Dialogue Evaluation), a method integrating SLMs and LLMs via adaptive weighting. Building on SLIDE, we further propose a Dual-Refinement Evaluation (DRE) method to enhance SLM-LLM integration: (1) SLM-generated insights guide the LLM to produce initial evaluations; (2) SLM-derived adjustments refine the LLM's scores for improved accuracy. Experiments demonstrate that DRE outperforms existing methods, showing stronger alignment with human judgment across diverse benchmarks. This work illustrates how combining small and large models can yield more reliable evaluation tools, particularly for open-ended tasks such as dialogue evaluation.

[Arxiv](https://arxiv.org/abs/2506.04516)