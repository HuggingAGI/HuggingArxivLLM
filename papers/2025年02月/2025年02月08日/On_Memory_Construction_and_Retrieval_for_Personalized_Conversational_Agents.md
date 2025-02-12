# # 个性化对话代理中的记忆构建与检索机制

发布时间：2025年02月08日

`Agent

摘要讨论了在长期对话中实现连贯和个性化体验的方法，特别是通过优化记忆单元和检索机制来提升对话系统的性能。这种方法属于智能体技术的改进，因此归类为Agent。` `对话系统`

> On Memory Construction and Retrieval for Personalized Conversational Agents

# 摘要

> 在长期对话中实现连贯且个性化的体验，现有方法通常通过基于轮次、会话级别或总结技术构建记忆库，执行基于检索增强的响应生成。本文中，我们开创性地提出两大发现：（1）记忆单元的粒度至关重要：无论是基于轮次、会话级别还是总结技术的方法，在记忆检索的准确性和语义质量方面均存在明显局限。（2）提示压缩方法如	extit{LLMLingua-2}可有效充当去噪机制，显著提升不同粒度下的记忆检索精度。基于此，我们提出SeCom方法：通过引入对话分割模型，构建基于主题段的记忆库，同时采用压缩记忆单元进行检索。实验结果表明，SeCom在LOCOMO和Long-MT-Bench+等长期对话基准测试中，显著超越基于轮次、会话级别及多种总结方法。此外，我们的对话分割方法在DialSeg711、TIAGE和SuperDialSeg等数据集上也展现出卓越性能。

> To deliver coherent and personalized experiences in long-term conversations, existing approaches typically perform retrieval augmented response generation by constructing memory banks from conversation history at either the turn-level, session-level, or through summarization techniques. In this paper, we present two key findings: (1) The granularity of memory unit matters: Turn-level, session-level, and summarization-based methods each exhibit limitations in both memory retrieval accuracy and the semantic quality of the retrieved content. (2) Prompt compression methods, such as \textit{LLMLingua-2}, can effectively serve as a denoising mechanism, enhancing memory retrieval accuracy across different granularities. Building on these insights, we propose SeCom, a method that constructs a memory bank with topical segments by introducing a conversation Segmentation model, while performing memory retrieval based on Compressed memory units. Experimental results show that SeCom outperforms turn-level, session-level, and several summarization-based methods on long-term conversation benchmarks such as LOCOMO and Long-MT-Bench+. Additionally, the proposed conversation segmentation method demonstrates superior performance on dialogue segmentation datasets such as DialSeg711, TIAGE, and SuperDialSeg.

[Arxiv](https://arxiv.org/abs/2502.05589)