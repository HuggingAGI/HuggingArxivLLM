# # 先思考，再分割：基于 GPT 思维链的高质量推理分割
在进行分割操作之前，先运用 GPT 的思维链进行高质量推理分割。

发布时间：2025年03月10日

`LLM应用` `计算机视觉`

> Think Before You Segment: High-Quality Reasoning Segmentation with GPT Chain of Thoughts

# 摘要

> 推理分割是一项极具挑战性的视觉语言任务，旨在根据复杂、隐含甚至非视觉的查询文本生成对应的分割掩膜。此前的研究将多模态大语言模型（MLLMs）与分割模型相结合，以应对这一难题。然而，这些方法在复杂场景下的分割质量往往不尽如人意，尤其在处理结构复杂、边界模糊、存在遮挡或与背景高度相似的域外对象时表现更差。本文提出了一种无需训练的推理分割框架ThinkFirst，该框架利用GPT的思维链能力来应对这些具有挑战性的场景。我们的方法允许GPT-4或其他强大的MLLM生成图像的详细思维链描述。这一总结性的描述随后被传递给一个语言指令驱动的分割助手，以辅助分割过程。我们的框架使用户能够轻松地通过多模态输入（如简单文本和图像涂鸦）与分割代理进行交互，以实现逐步细化或沟通。我们在多样化的对象上评估了ThinkFirst的性能。大量实验表明，这种零样本-思维链方法在定性和定量上都显著提升了基础推理分割代理的表现，同时在经过ThinkFirst处理后，对用户提供的提示的敏感性和依赖性降低。

> Reasoning segmentation is a challenging vision-language task that aims to output the segmentation mask with respect to a complex, implicit, and even non-visual query text. Previous works incorporated multimodal Large Language Models (MLLMs) with segmentation models to approach the difficult problem. However, their segmentation quality often falls short in complex cases, particularly when dealing with out-of-domain objects with intricate structures, blurry boundaries, occlusions, or high similarity with surroundings. In this paper, we introduce ThinkFirst, a training-free reasoning segmentation framework that leverages GPT's chain of thought to address these challenging cases. Our approach allows GPT-4o or other powerful MLLMs to generate a detailed, chain-of-thought description of an image. This summarized description is then passed to a language-instructed segmentation assistant to aid the segmentation process. Our framework allows users to easily interact with the segmentation agent using multimodal inputs, such as easy text and image scribbles, for successive refinement or communication. We evaluate the performance of ThinkFirst on diverse objects. Extensive experiments show that, this zero-shot-CoT approach significantly improves the vanilla reasoning segmentation agent, both qualitatively and quantitatively, while being less sensitive or critical to user-supplied prompts after Thinking First.

[Arxiv](https://arxiv.org/abs/2503.07503)