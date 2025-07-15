# 声音背后的推手：多模态大语言模型助力音频隐私属性分析揭秘

发布时间：2025年07月14日

`LLM应用` `隐私保护` `音频处理`

> The Man Behind the Sound: Demystifying Audio Private Attribute Profiling via Multimodal Large Language Model Agents

# 摘要

> 我们发现了一种与多模态大型语言模型（MLLMs）相关的新型隐私风险：从音频数据中推断敏感个人信息的能力，我们称之为音频隐私属性画像。这种能力具有极大威胁性，因为音频可以在不被察觉的情况下秘密捕获。与图像和文本相比，音频的独特特征（如音调和音高）使其可以被用来进行更详细的画像。然而，目前在理解MLLMs从音频中进行隐私属性画像时面临两个主要挑战：(1) 缺乏带有敏感属性标注的音频基准数据集；(2) 当前MLLMs直接从音频中推断属性的能力有限。为了解决这些问题，我们推出了AP^2，一个由真实世界数据构建的音频基准数据集，且所有数据均标注了敏感属性标签。此外，我们提出了Gifts，一个混合多智能体框架，通过结合音频语言模型（ALMs）和大型语言模型（LLMs）的互补优势来提升推断能力。Gifts利用LLM引导ALM推断敏感属性，随后对ALM的推断结果进行取证分析和整合，有效克服了现有ALMs在生成长上下文响应时的严重幻觉问题。我们的实验表明，Gifts在推断敏感属性方面显著优于传统方法。最后，我们探索了模型级和数据级的防御策略，以降低音频隐私属性画像的风险。我们的研究验证了使用MLLMs进行基于音频的隐私攻击的可行性，强调了构建强大防御机制的必要性，并为未来研究提供了数据集和框架支持。

> Our research uncovers a novel privacy risk associated with multimodal large language models (MLLMs): the ability to infer sensitive personal attributes from audio data -- a technique we term audio private attribute profiling. This capability poses a significant threat, as audio can be covertly captured without direct interaction or visibility. Moreover, compared to images and text, audio carries unique characteristics, such as tone and pitch, which can be exploited for more detailed profiling. However, two key challenges exist in understanding MLLM-employed private attribute profiling from audio: (1) the lack of audio benchmark datasets with sensitive attribute annotations and (2) the limited ability of current MLLMs to infer such attributes directly from audio. To address these challenges, we introduce AP^2, an audio benchmark dataset that consists of two subsets collected and composed from real-world data, and both are annotated with sensitive attribute labels. Additionally, we propose Gifts, a hybrid multi-agent framework that leverages the complementary strengths of audio-language models (ALMs) and large language models (LLMs) to enhance inference capabilities. Gifts employs an LLM to guide the ALM in inferring sensitive attributes, then forensically analyzes and consolidates the ALM's inferences, overcoming severe hallucinations of existing ALMs in generating long-context responses. Our evaluations demonstrate that Gifts significantly outperforms baseline approaches in inferring sensitive attributes. Finally, we investigate model-level and data-level defense strategies to mitigate the risks of audio private attribute profiling. Our work validates the feasibility of audio-based privacy attacks using MLLMs, highlighting the need for robust defenses, and provides a dataset and framework to facilitate future research.

[Arxiv](https://arxiv.org/abs/2507.10016)