# 亚当梅姆：自适应探测多模态大型语言模型的有害性推理能力

发布时间：2025年07月02日

`其他` `社交媒体` `人工智能`

> AdamMeme: Adaptively Probe the Reasoning Capacity of Multimodal Large Language Models on Harmfulness

# 摘要

> 社交媒体时代，多模态表情包的泛滥对多模态大型语言模型（mLLMs）理解表情包危害性的能力提出了更高要求。现有的mLLMs有害表情包理解评估基准依赖于基于准确率的静态数据集和模型不可知的评估方法。然而，由于网络表情包的动态演变，这些基准测试在提供及时、全面评估方面存在局限性。为此，我们提出了AdamMeme——一个灵活的、基于智能体的评估框架，能够自适应地探测mLLMs在解析表情包危害性方面的推理能力。通过多智能体协作，AdamMeme通过迭代更新表情包数据并加入具有挑战性的样本，提供了全面的评估，从而揭示了mLLMs在解释危害性方面存在的特定局限性。实验结果表明，我们的框架系统性地揭示了不同目标mLLMs的表现差异，并对模型特有的弱点进行了深入的细粒度分析。我们的代码可在https://github.com/Lbotirx/AdamMeme获取。

> The proliferation of multimodal memes in the social media era demands that multimodal Large Language Models (mLLMs) effectively understand meme harmfulness. Existing benchmarks for assessing mLLMs on harmful meme understanding rely on accuracy-based, model-agnostic evaluations using static datasets. These benchmarks are limited in their ability to provide up-to-date and thorough assessments, as online memes evolve dynamically. To address this, we propose AdamMeme, a flexible, agent-based evaluation framework that adaptively probes the reasoning capabilities of mLLMs in deciphering meme harmfulness. Through multi-agent collaboration, AdamMeme provides comprehensive evaluations by iteratively updating the meme data with challenging samples, thereby exposing specific limitations in how mLLMs interpret harmfulness. Extensive experiments show that our framework systematically reveals the varying performance of different target mLLMs, offering in-depth, fine-grained analyses of model-specific weaknesses. Our code is available at https://github.com/Lbotirx/AdamMeme.

[Arxiv](https://arxiv.org/abs/2507.01702)