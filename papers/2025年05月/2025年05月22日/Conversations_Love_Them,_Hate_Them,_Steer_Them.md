# 对话：爱之，恨之，驾驭之

发布时间：2025年05月22日

`LLM应用` `对话AI` `情感计算`

> Conversations: Love Them, Hate Them, Steer Them

# 摘要

> 大型语言模型（LLMs）的对话流畅性不断提升，但如何赋予它们细腻、人性化的表情表达仍是一个重要挑战。现有的对齐技术往往局限于表面输出的调整，或是需要繁琐的微调。本文提出了一种基于激活工程的解决方案，成功引导 LLaMA 3.1-8B 展现出更丰富的情感层次。我们首先通过归因补丁技术，识别出在诊断对话任务中具有因果影响力的组件，从而找到关键的干预点。接着，我们从对比文本对（目标情绪的正例与负例）生成的激活差异中，提取出表情表达向量。将这些向量应用于新的对话提示，显著提升了响应的情感特征：引导后的回复不仅表现出更高的积极情感（如喜悦、信任），还更频繁地使用第一人称代词，显示出更强的个人参与感。我们的研究提供了一种精确且可解释的方法，用于控制 LLM 中的具体表情属性，为开发更对齐、更具同理心的对话 AI 开辟了新的道路。

> Large Language Models (LLMs) demonstrate increasing conversational fluency, yet instilling them with nuanced, human-like emotional expression remains a significant challenge. Current alignment techniques often address surface-level output or require extensive fine-tuning. This paper demonstrates that targeted activation engineering can steer LLaMA 3.1-8B to exhibit more human-like emotional nuances. We first employ attribution patching to identify causally influential components, to find a key intervention locus by observing activation patterns during diagnostic conversational tasks. We then derive emotional expression vectors from the difference in the activations generated by contrastive text pairs (positive vs. negative examples of target emotions). Applying these vectors to new conversational prompts significantly enhances emotional characteristics: steered responses show increased positive sentiment (e.g., joy, trust) and more frequent first-person pronoun usage, indicative of greater personal engagement. Our findings offer a precise and interpretable method for controlling specific emotional attributes in LLMs, contributing to developing more aligned and empathetic conversational AI.

[Arxiv](https://arxiv.org/abs/2505.17413)