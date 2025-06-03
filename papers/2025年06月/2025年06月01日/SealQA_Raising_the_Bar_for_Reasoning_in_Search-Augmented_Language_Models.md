# SealQA：重新定义搜索增强语言模型的推理标准

发布时间：2025年06月01日

`LLM应用` `信息检索` `问答系统`

> SealQA: Raising the Bar for Reasoning in Search-Augmented Language Models

# 摘要

> 我们很高兴推出 SealQA，这是一个全新的基准测试，专门用于评估搜索增强型语言模型在处理事实性问题时的表现，尤其在面对网络搜索中出现的矛盾、噪声或无用结果时。SealQA 包含三个版本：(1) Seal-0（核心版本）和 (2) Seal-Hard，这两个版本专注于评估模型的事实准确性和推理能力，其中 Seal-0 特别挑选了极具挑战性的问题，即使像 GPT-4.1 这样的聊天模型也几乎无法正确回答；(3) LongSeal，它将 SealQA 扩展至“大海捞针”场景，用于测试长上下文和多文档推理能力。通过我们的评估发现，当前模型仍存在显著限制：即使是最前沿的 LLM 在 SealQA 的所有版本中表现均不尽如人意。在 Seal-0 上，配备 o3 和 o4-mini 等工具的最前沿智能体模型在最佳推理状态下，准确率也只有 17.1% 和 6.3%。我们还发现，像 DeepSeek-R1-671B 和 o3-mini 这样的先进推理模型极易受到噪声搜索结果的影响。值得注意的是，增加测试时的计算资源并未显著提升 o3-mini、o4-mini 和 o3 的表现，性能往往迅速达到 plateau 或甚至下降。此外，尽管近期模型较少受到“迷失在中间”问题的影响，但在 LongSeal 中面对大量干扰项时，它们仍难以可靠地识别相关文档。为了推动未来研究，我们在 huggingface.co/datasets/vtllms/sealqa 上开放了 SealQA 数据集，欢迎各位研究者下载使用。


> We introduce SealQA, a new challenge benchmark for evaluating SEarch-Augmented Language models on fact-seeking questions where web search yields conflicting, noisy, or unhelpful results. SealQA comes in three flavors: (1) Seal-0 (main) and (2) Seal-Hard, which assess factual accuracy and reasoning capabilities, with Seal-0 focusing on the most challenging questions where chat models (e.g., GPT-4.1) typically achieve near-zero accuracy; and (3) LongSeal, which extends SealQA to test long-context, multi-document reasoning in "needle-in-a-haystack" settings. Our evaluation reveals critical limitations in current models: Even frontier LLMs perform poorly across all SealQA flavors. On Seal-0, frontier agentic models equipped with tools like o3 and o4-mini achieve only 17.1% and 6.3% accuracy, respectively, at their best reasoning efforts. We find that advanced reasoning models such as DeepSeek-R1-671B and o3-mini are highly vulnerable to noisy search results. Notably, increasing test-time compute does not yield reliable gains across o3-mini, o4-mini, and o3, with performance often plateauing or even declining early. Additionally, while recent models are less affected by the "lost-in-the-middle" issue, they still fail to reliably identify relevant documents in LongSeal when faced with numerous distractors. To facilitate future work, we release SealQA at huggingface.co/datasets/vtllms/sealqa.

[Arxiv](https://arxiv.org/abs/2506.01062)