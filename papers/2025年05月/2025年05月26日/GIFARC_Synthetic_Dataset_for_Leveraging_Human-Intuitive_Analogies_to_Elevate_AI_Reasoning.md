# GIFARC: 通过人类直观类比提升AI推理能力的合成数据集

发布时间：2025年05月26日

`LLM应用` `AI教育`

> GIFARC: Synthetic Dataset for Leveraging Human-Intuitive Analogies to Elevate AI Reasoning

# 摘要

> 抽象与推理语料库（ARC）对通用AI能力提出了严格考验，要求求解器仅从少量示例中推断抽象模式。尽管深度学习取得了长足进步，但目前最先进的模型在2024 ARC竞赛中仍仅达到40-55%的准确率，表明其推理水平与人类相比仍有显著差距。本研究旨在通过引入一个受类比启发的ARC数据集GIFARC来缩小这一差距。我们利用大型语言模型（LLMs）和视觉语言模型（VLMs），从包含类比的各类GIF图像中合成新的ARC风格任务。每个新任务都配对了真实类比，提供了视觉变换与日常概念之间的明确映射。通过将 robust 人类直观类比嵌入ARC风格任务，GIFARC引导AI代理在进行暴力模式搜索之前以类比方式评估任务，从而有效降低问题复杂度并构建更简洁、更易为人理解的解决方案。我们实证验证，借助GIFARC以类比方式引导LLM，能够使LLM的任务解决方式与人类的类比思维方式保持一致。


> The Abstraction and Reasoning Corpus (ARC) poses a stringent test of general AI capabilities, requiring solvers to infer abstract patterns from only a handful of examples. Despite substantial progress in deep learning, state-of-the-art models still achieve accuracy rates of merely 40-55% on 2024 ARC Competition, indicative of a significant gap between their performance and human-level reasoning. In this work, we seek to bridge that gap by introducing an analogy-inspired ARC dataset, GIFARC. Leveraging large language models (LLMs) and vision-language models (VLMs), we synthesize new ARC-style tasks from a variety of GIF images that include analogies. Each new task is paired with ground-truth analogy, providing an explicit mapping between visual transformations and everyday concepts. By embedding robust human-intuitive analogies into ARC-style tasks, GIFARC guides AI agents to evaluate the task analogically before engaging in brute-force pattern search, thus efficiently reducing problem complexity and build a more concise and human-understandable solution. We empirically validate that guiding LLM with analogic approach with GIFARC affects task-solving approaches of LLMs to align with analogic approach of human.

[Arxiv](https://arxiv.org/abs/2505.20672)