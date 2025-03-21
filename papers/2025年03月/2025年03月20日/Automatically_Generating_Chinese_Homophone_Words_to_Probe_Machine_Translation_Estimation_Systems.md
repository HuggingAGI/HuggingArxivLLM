# 用于探查机器翻译质量评估系统的中文同音词自动生成方法

发布时间：2025年03月20日

`LLM应用` `机器翻译`

> Automatically Generating Chinese Homophone Words to Probe Machine Translation Estimation Systems

# 摘要

> 评估用户生成内容（UGC）的机器翻译（MT）面临独特挑战，尤其是如何保留原文中的情感细微差别。近期研究提出了与情感相关的数据集、框架和模型，无需参考译文即可自动评估中文UGC的MT质量。然而，这些模型在保留情感细微差别方面的鲁棒性尚未得到充分探索。为填补这一空白，我们提出了一种基于信息论的创新方法，通过利用自信息量的概念，生成与情感相关的具有挑战性的中文同音词。我们的方法生成了那些被观察到会导致情感保留翻译错误的同音词，并揭示了MT系统及其在处理情感UGC时的评估方法的漏洞。我们通过人工评估生成同音词的质量来评估我们方法的有效性，并将其与现有方法进行比较，结果显示我们的方法与人工判断的关联性更高。生成的中文同音词及其人工翻译被用于生成扰动，并测试现有质量评估模型的鲁棒性，包括多任务学习训练的模型、多语言语言模型的微调变体，以及大型语言模型（LLMs）。我们的结果显示，规模更大的LLMs在面对此类扰动时表现出更高的稳定性和鲁棒性。我们公开了数据和代码，以支持可重复研究和进一步探索。

> Evaluating machine translation (MT) of user-generated content (UGC) involves unique challenges such as checking whether the nuance of emotions from the source are preserved in the target text. Recent studies have proposed emotion-related datasets, frameworks and models to automatically evaluate MT quality of Chinese UGC, without relying on reference translations. However, whether these models are robust to the challenge of preserving emotional nuances has been left largely unexplored. To address this gap, we introduce a novel method inspired by information theory which generates challenging Chinese homophone words related to emotions, by leveraging the concept of self-information. Our approach generates homophones that were observed to cause translation errors in emotion preservation, and exposes vulnerabilities in MT systems and their evaluation methods when tackling emotional UGC. We evaluate the efficacy of our method using human evaluation for the quality of these generated homophones, and compare it with an existing one, showing that our method achieves higher correlation with human judgments. The generated Chinese homophones, along with their manual translations, are utilized to generate perturbations and to probe the robustness of existing quality evaluation models, including models trained using multi-task learning, fine-tuned variants of multilingual language models, as well as large language models (LLMs). Our results indicate that LLMs with larger size exhibit higher stability and robustness to such perturbations. We release our data and code for reproducibility and further research.

[Arxiv](https://arxiv.org/abs/2503.16158)