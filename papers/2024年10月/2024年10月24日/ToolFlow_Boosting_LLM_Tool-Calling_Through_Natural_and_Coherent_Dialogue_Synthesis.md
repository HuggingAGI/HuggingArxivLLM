# ToolFlow: 利用自然流畅的对话合成增强LLM工具调用

发布时间：2024年10月24日

`Agent

理由：这篇论文主要讨论了通过多代理交互式合成对话数据来提升大型语言模型（LLMs）的工具调用能力。论文中提到的“多代理交互式合成对话数据”和“工具调用数据合成管道 ToolFlow”都涉及到多个代理（Agent）之间的协作和交互，因此这篇论文应归类为Agent。` `工具调用`

> ToolFlow: Boosting LLM Tool-Calling Through Natural and Coherent Dialogue Synthesis

# 摘要

> # 摘要
监督微调（SFT）是提升大型语言模型（LLMs）工具调用能力的常用方法，通常依赖于合成数据。当前的数据合成流程包括工具采样、需求制定和调用语句生成。然而，随机采样的工具缺乏关联性，难以组合，导致数据多样性不足。此外，现有方法忽视了对话轮次间的连贯性，使得合成数据与现实场景脱节。为此，我们提出了基于图的采样策略，以获取更相关的工具组合，并设计了计划生成策略，用于指导连贯对话的合成。我们将这两种策略结合，通过多代理交互式合成对话数据，构建了工具调用数据合成管道 ToolFlow。数据质量评估显示，ToolFlow 合成的对话在自然性和连贯性上均有显著提升。最后，我们利用 ToolFlow 生成的 8,000 条合成对话对 LLaMA-3.1-8B 进行 SFT，结果显示该模型在工具调用性能上可与 GPT-4 媲美甚至超越，同时保持了强大的通用能力。

> Supervised fine-tuning (SFT) is a common method to enhance the tool calling capabilities of Large Language Models (LLMs), with the training data often being synthesized. The current data synthesis process generally involves sampling a set of tools, formulating a requirement based on these tools, and generating the call statements. However, tools sampled randomly lack relevance, making them difficult to combine and thus reducing the diversity of the data. Additionally, current work overlooks the coherence between turns of dialogues, leading to a gap between the synthesized data and real-world scenarios. To address these issues, we propose a Graph-based Sampling strategy to sample more relevant tool combinations, and a Planned-generation strategy to create plans that guide the synthesis of coherent dialogues. We integrate these two strategies and enable multiple agents to synthesize the dialogue data interactively, resulting in our tool-calling data synthesis pipeline ToolFlow. Data quality assessments demonstrate improvements in the naturalness and coherence of our synthesized dialogues. Finally, we apply SFT on LLaMA-3.1-8B using 8,000 synthetic dialogues generated with ToolFlow. Results show that the model achieves tool-calling performance comparable to or even surpassing GPT-4, while maintaining strong general capabilities.

[Arxiv](https://arxiv.org/abs/2410.18447)