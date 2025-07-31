# # PATENTWRITER：利用大型语言模型进行专利撰写的基准研究

发布时间：2025年07月30日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在专利写作中的应用，特别是通过提出一个基准框架来评估这些模型生成专利摘要的能力。研究的重点是模型在实际任务中的表现和应用，因此归类为LLM应用。` `知识产权`

> PATENTWRITER: A Benchmarking Study for Patent Drafting with LLMs

# 摘要

> 大型语言模型（LLMs）已在多个重要领域中展现出变革性的潜力。本文旨在通过利用LLMs实现专利写作的范式转变，以克服繁琐的专利申请流程。在此工作中，我们提出了PATENTWRITER，这是首个用于评估LLMs在专利摘要生成方面表现的统一基准框架。基于专利的第一项权利要求，我们在零样本、少样本和链式思考提示策略下，对包括GPT-4和LLaMA-3在内的六种领先LLMs进行评估，以生成专利摘要。我们的基准PATENTWRITER不仅限于表面评估：我们采用一套全面的指标系统来评估输出质量，包括标准NLP指标（如BLEU、ROUGE、BERTScore）、三种类型输入扰动下的鲁棒性，以及在两项下游专利分类和检索任务中的适用性。我们还进行了风格分析，以评估摘要的长度、可读性和语气。实验结果表明，现代LLMs能够生成高保真且风格合适的专利摘要，往往超越特定领域的基线。我们的代码和数据集已开源，以支持可重复性和未来研究。

> Large language models (LLMs) have emerged as transformative approaches in several important fields. This paper aims for a paradigm shift for patent writing by leveraging LLMs to overcome the tedious patent-filing process. In this work, we present PATENTWRITER, the first unified benchmarking framework for evaluating LLMs in patent abstract generation. Given the first claim of a patent, we evaluate six leading LLMs -- including GPT-4 and LLaMA-3 -- under a consistent setup spanning zero-shot, few-shot, and chain-of-thought prompting strategies to generate the abstract of the patent. Our benchmark PATENTWRITER goes beyond surface-level evaluation: we systematically assess the output quality using a comprehensive suite of metrics -- standard NLP measures (e.g., BLEU, ROUGE, BERTScore), robustness under three types of input perturbations, and applicability in two downstream patent classification and retrieval tasks. We also conduct stylistic analysis to assess length, readability, and tone. Experimental results show that modern LLMs can generate high-fidelity and stylistically appropriate patent abstracts, often surpassing domain-specific baselines. Our code and dataset are open-sourced to support reproducibility and future research.

[Arxiv](https://arxiv.org/abs/2507.22387)