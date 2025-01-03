# DeCoRe: 对比检索头解码，有效缓解幻觉

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的幻觉问题，并提出了一种新的解码策略（DeCoRe）来减少幻觉。研究集中在Transformer架构中的特定注意力头（检索头）的作用，并通过对比基础LLM和屏蔽LLM的输出来减少幻觉。这些内容涉及LLM的内部机制和理论改进，因此应归类为LLM理论。` `人工智能`

> DeCoRe: Decoding by Contrasting Retrieval Heads to Mitigate Hallucinations

# 摘要

> 大型语言模型（LLMs）常出现幻觉，生成不忠实或事实错误的输出。最近研究发现，Transformer架构中的特定注意力头（称为检索头）负责提取上下文信息。我们假设屏蔽这些检索头会诱发幻觉，而对比基础LLM和屏蔽LLM的输出可减少幻觉。为此，我们提出了DeCoRe（通过对比检索头解码），这是一种无需训练的解码策略，能放大上下文和模型参数中的信息。DeCoRe通过动态对比基础LLM和屏蔽LLM的输出，以条件熵为引导，有效减少幻觉响应。实验表明，DeCoRe在摘要（XSum提升18.6%）、指令跟随（MemoTrap提升10.9%）和开卷问答（NQ-Open提升2.4%，NQ-Swap提升5.5%）等任务中显著提升了性能。

> Large Language Models (LLMs) often hallucinate, producing unfaithful or factually incorrect outputs by misrepresenting the provided context or incorrectly recalling internal knowledge. Recent studies have identified specific attention heads within the Transformer architecture, known as retrieval heads, responsible for extracting relevant contextual information. We hypothesise that masking these retrieval heads can induce hallucinations and that contrasting the outputs of the base LLM and the masked LLM can reduce hallucinations. To this end, we propose Decoding by Contrasting Retrieval Heads (DeCoRe), a novel training-free decoding strategy that amplifies information found in the context and model parameters. DeCoRe mitigates potentially hallucinated responses by dynamically contrasting the outputs of the base LLM and the masked LLM, using conditional entropy as a guide. Our extensive experiments confirm that DeCoRe significantly improves performance on tasks requiring high contextual faithfulness, such as summarisation (XSum by 18.6%), instruction following (MemoTrap by 10.9%), and open-book question answering (NQ-Open by 2.4% and NQ-Swap by 5.5%).

[Arxiv](https://arxiv.org/abs/2410.18860)