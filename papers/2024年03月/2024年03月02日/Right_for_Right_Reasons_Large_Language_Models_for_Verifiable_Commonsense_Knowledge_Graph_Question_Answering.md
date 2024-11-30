# 追求“因为对所以对”——大型语言模型助力可靠解答常识知识图谱问题

发布时间：2024年03月02日

`LLM应用`

> Right for Right Reasons: Large Language Models for Verifiable Commonsense Knowledge Graph Question Answering

# 摘要

> 知识图谱问答技术（KGQA）借助知识图谱中蕴含的关系信息来解答自然语言问题，而最近大放异彩的大型语言模型（LLMs）及其实现的卓越推理能力，正逐步被应用于此类问题解决中。然而，当前的方法主要聚焦于回答客观事实类问题，而对于用户日常可能提出的包含常识推理的问题，比如“同时参观维纳斯·维伦道夫雕像和夏季奥运会是否需要分开办理签证？”却尚未得到有效解决。在本研究中，我们发现现存基于LLM的KGQA方法在面对此类涉及长尾实体（如非主流或新近出现的实体）的问题时，尤其是在推理过程中容易产生臆断错误，这对它们在真实场景下的应用构成了限制，尤其是由于其推理路径难以核实。为此，我们创新性地提出了Right for Right Reasons（简称R3）这一基于常识的KGQA方法论，它能够从原理层面挖掘并显现LLMs内在的常识知识，并确保每一个基于事实的推理步骤都能准确锚定在知识图谱的三元组上，从而形成一个可验证的推理流程。经过跨三个不同任务——问题回答、主张验证以及偏好匹配——的实验证明，R3展现出了明显优势，不仅超越了现有方法，还有效降低了臆断错误和推理失误的发生率。

> Knowledge Graph Question Answering (KGQA) methods seek to answer Natural Language questions using the relational information stored in Knowledge Graphs (KGs). With the recent advancements of Large Language Models (LLMs) and their remarkable reasoning abilities, there is a growing trend to leverage them for KGQA. However, existing methodologies have only focused on answering factual questions, e.g., "In which city was Silvio Berlusconi's first wife born?", leaving questions involving commonsense reasoning that real-world users may pose more often, e.g., "Do I need separate visas to see the Venus of Willendorf and attend the Olympics this summer?" unaddressed. In this work, we first observe that existing LLM-based methods for KGQA struggle with hallucination on such questions, especially on queries targeting long-tail entities (e.g., non-mainstream and recent entities), thus hindering their applicability in real-world applications especially since their reasoning processes are not easily verifiable. In response, we propose Right for Right Reasons (R3), a commonsense KGQA methodology that allows for a verifiable reasoning procedure by axiomatically surfacing intrinsic commonsense knowledge of LLMs and grounding every factual reasoning step on KG triples. Through experimental evaluations across three different tasks--question answering, claim verification, and preference matching--our findings showcase R3 as a superior approach, outperforming existing methodologies and notably reducing instances of hallucination and reasoning errors.

[Arxiv](https://arxiv.org/abs/2403.01390)