# 错位的积极性：失准积极态度如何削弱在线支持性对话

发布时间：2025年09月12日

`LLM应用` `医疗健康`

> Incongruent Positivity: When Miscalibrated Positivity Undermines Online Supportive Conversations

# 摘要

> 在情感支持对话中，善意的积极回应有时可能弄巧成拙，让人感觉敷衍、轻描淡写或过于乐观。我们将这种“不一致积极”现象定义为人类和LLM生成回应中积极支持表达的校准偏差。为此，我们从Reddit收集了不同情感强度的真实用户-助手对话，并基于相同语境用LLM生成了补充回应。我们按情感强度将对话分为两类：轻微级（涉及关系紧张和日常建议）和严重级（涉及悲伤和焦虑话题）。这种分类便于比较分析支持性回应在低风险和高风险情境中的差异。分析发现，LLM更容易通过敷衍或轻描淡写的语气表现出不切实际的积极倾向，尤其是在高风险情境中。为深入探究这一现象的内在机制，我们在包含强弱情感反应的数据集上微调了LLM。此外，我们构建了一个弱监督多标签分类器集成（DeBERTa与MentalBERT），该集成在轻微和严重两类问题中均提升了对不一致积极回应类型的检测效果。研究结果表明，我们需超越生成泛泛的积极回应，转而探索“一致支持”策略，以平衡积极情感表达与情感共情。这一方法为LLM适配在线支持对话中的情感期望提供了思路，有望推动情境感知与信任维护的在线对话系统发展。

> In emotionally supportive conversations, well-intended positivity can sometimes misfire, leading to responses that feel dismissive, minimizing, or unrealistically optimistic. We examine this phenomenon of incongruent positivity as miscalibrated expressions of positive support in both human and LLM generated responses. To this end, we collected real user-assistant dialogues from Reddit across a range of emotional intensities and generated additional responses using large language models for the same context. We categorize these conversations by intensity into two levels: Mild, which covers relationship tension and general advice, and Severe, which covers grief and anxiety conversations. This level of categorization enables a comparative analysis of how supportive responses vary across lower and higher stakes contexts. Our analysis reveals that LLMs are more prone to unrealistic positivity through dismissive and minimizing tone, particularly in high-stakes contexts. To further study the underlying dimensions of this phenomenon, we finetune LLMs on datasets with strong and weak emotional reactions. Moreover, we developed a weakly supervised multilabel classifier ensemble (DeBERTa and MentalBERT) that shows improved detection of incongruent positivity types across two sorts of concerns (Mild and Severe). Our findings shed light on the need to move beyond merely generating generic positive responses and instead study the congruent support measures to balance positive affect with emotional acknowledgment. This approach offers insights into aligning large language models with affective expectations in the online supportive dialogue, paving the way toward context-aware and trust preserving online conversation systems.

[Arxiv](https://arxiv.org/abs/2509.10184)