# 信心与批判：对大型语言模型（LLM）自我纠正能力的分解

发布时间：2024年12月27日

`LLM应用` `人工智能`

> Confidence v.s. Critique: A Decomposition of Self-Correction Capability for LLMs

# 摘要

> 大型语言模型（LLMs）能够对自身生成的回答进行纠正，不过也存在自我纠正后准确性降低的情况。为了深入理解自我纠正，我们致力于对 LLMs 的自我纠正行为进行分解、评估和分析。通过列举并分析自我纠正前后答案的正确性，我们把自我纠正能力分解为信心（有信心改正答案）和批判（将错误答案改正）能力，从概率角度提出了两个指标来衡量这两种能力，还提出了另一个用于整体自我纠正能力评估的指标。基于我们的分解和评估指标，我们开展了大量实验，并得出了一些经验性结论。比如，我们发现不同的模型会有不同的表现：有些模型信心满满，而有些模型则更具批判性。我们还发现，在通过提示或上下文学习来操控模型自我纠正行为时，这两种能力存在此消彼长的关系（即提升一种能力会导致另一种能力下降）。此外，我们找到了一种简单却有效的策略，即通过转换监督微调（SFT）数据格式来提升自我纠正能力，我们的策略在这两种能力上都优于常规的 SFT，并且在自我纠正后能达到更高的准确性。我们的代码将在 GitHub 上公开。

> Large Language Models (LLMs) can correct their self-generated responses, but a decline in accuracy after self-correction is also witnessed. To have a deeper understanding of self-correction, we endeavor to decompose, evaluate, and analyze the self-correction behaviors of LLMs. By enumerating and analyzing answer correctness before and after self-correction, we decompose the self-correction capability into confidence (being confident to correct answers) and critique (turning wrong answers to correct) capabilities, and propose two metrics from a probabilistic perspective to measure these 2 capabilities, along with another metric for overall self-correction capability evaluation. Based on our decomposition and evaluation metrics, we conduct extensive experiments and draw some empirical conclusions. For example, we find different models can exhibit distinct behaviors: some models are confident while others are more critical. We also find the trade-off between the two capabilities (i.e. improving one can lead to a decline in the other) when manipulating model self-correction behavior by prompts or in-context learning. Further, we find a simple yet efficient strategy to improve self-correction capability by transforming Supervision Fine-Tuning (SFT) data format, and our strategy outperforms vanilla SFT in both capabilities and achieves much higher accuracy after self-correction. Our code will be publicly available on GitHub.

[Arxiv](https://arxiv.org/abs/2412.19513)