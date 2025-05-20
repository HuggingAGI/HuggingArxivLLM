# 学习辅助任务显著提升无参考幻觉检测效果，应用于开放领域的长文本生成任务中

发布时间：2025年05月18日

`LLM应用` `大型语言模型`

> Learning Auxiliary Tasks Improves Reference-Free Hallucination Detection in Open-Domain Long-Form Generation

# 摘要

> 幻觉（即生成事实性错误信息）仍是大型语言模型（LLMs）面临的重要挑战，尤其是在开放领域长文本生成中。现有针对长文本任务中幻觉检测的方法要么局限于特定领域，要么严重依赖外部事实核查工具，这些工具并不总是可用。

本研究系统性地探讨了开放领域长文本回复中无需参考的幻觉检测。研究发现，仅凭模型的内部状态（如输出概率和熵）无法可靠地区分事实性内容与幻觉内容。为了提升检测效果，我们探索了多种现有方法，包括基于提示的方法、探测技术和微调，其中微调被证明是最有效的。为了进一步提高检测精度，我们提出了一种新范式，名为RATE-FT，通过为模型添加辅助任务，使其能够与幻觉检测的主要任务联合学习。通过使用多种模型家族和数据集进行广泛实验和分析，我们验证了该方法的有效性和通用性，例如在LongFact数据集上比通用微调方法高出3%。


> Hallucination, the generation of factually incorrect information, remains a significant challenge for large language models (LLMs), especially in open-domain long-form generation. Existing approaches for detecting hallucination in long-form tasks either focus on limited domains or rely heavily on external fact-checking tools, which may not always be available.
  In this work, we systematically investigate reference-free hallucination detection in open-domain long-form responses. Our findings reveal that internal states (e.g., model's output probability and entropy) alone are insufficient for reliably (i.e., better than random guessing) distinguishing between factual and hallucinated content. To enhance detection, we explore various existing approaches, including prompting-based methods, probing, and fine-tuning, with fine-tuning proving the most effective. To further improve the accuracy, we introduce a new paradigm, named RATE-FT, that augments fine-tuning with an auxiliary task for the model to jointly learn with the main task of hallucination detection. With extensive experiments and analysis using a variety of model families & datasets, we demonstrate the effectiveness and generalizability of our method, e.g., +3% over general fine-tuning methods on LongFact.

[Arxiv](https://arxiv.org/abs/2505.12265)