# MultiQ&A：基于自动众包问题扰动与答案的鲁棒性测量分析

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何通过MultiQ&A方法来评估大型语言模型（LLM）生成答案的鲁棒性和一致性，特别是在面对问题扰动时的表现。这涉及到LLM在实际应用中的表现和评估，属于LLM应用的范畴。` `人工智能`

> MultiQ&A: An Analysis in Measuring Robustness via Automated Crowdsourcing of Question Perturbations and Answers

# 摘要

> 在LLMs的机构采用过程中，一个主要挑战是其生成响应时易产生幻觉。为此，我们提出了MultiQ&A，一种系统评估LLM生成答案鲁棒性和一致性的方法。MultiQ&A通过独立LLM代理大规模众包问题扰动及其答案，实验共检查了190万个问题扰动和230万个答案。结果显示，如gpt-3.5-turbo等集成LLM在扰动下仍保持较高鲁棒性和一致性。MultiQ&A为响应生成领域提供了清晰度，有效检查分歧和变异性，为机构采用LLM提供了测量信心、一致性和幻觉量化的潜在框架。

> One critical challenge in the institutional adoption journey of Large Language Models (LLMs) stems from their propensity to hallucinate in generated responses. To address this, we propose MultiQ&A, a systematic approach for evaluating the robustness and consistency of LLM-generated answers. We demonstrate MultiQ&A's ability to crowdsource question perturbations and their respective answers through independent LLM agents at scale. Our experiments culminated in the examination of 1.9 million question perturbations and 2.3 million answers. Furthermore, MultiQ&A shows that ensembled LLMs, such as gpt-3.5-turbo, remain relatively robust and consistent under perturbations. MultiQ&A provides clarity in the response generation space, offering an effective method for inspecting disagreements and variability. Therefore, our system offers a potential framework for institutional LLM adoption with the ability to measure confidence, consistency, and the quantification of hallucinations.

[Arxiv](https://arxiv.org/abs/2502.03711)