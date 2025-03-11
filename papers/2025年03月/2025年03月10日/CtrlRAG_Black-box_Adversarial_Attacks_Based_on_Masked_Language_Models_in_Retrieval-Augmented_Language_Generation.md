# CtrlRAG：基于遮蔽语言模型的黑盒对抗攻击在检索增强语言生成中的应用

发布时间：2025年03月10日

`RAG` `生成模型`

> CtrlRAG: Black-box Adversarial Attacks Based on Masked Language Models in Retrieval-Augmented Language Generation

# 摘要

> 检索增强生成（RAG）系统通过整合外部知识库来增强大型语言模型（LLMs）。然而，这种整合也带来了新的安全威胁：攻击者可利用检索机制向知识库注入恶意内容，进而影响生成回复。针对这一攻击途径，我们提出了一种新型攻击方法 CtrlRAG，专门针对黑盒环境下的 RAG 系统。与现有方法不同，CtrlRAG 基于遮蔽语言模型（MLM）引入了动态优化机制，可根据检索上下文变化实时调整恶意内容。实验结果表明，CtrlRAG 在情感操控和幻觉放大两个目标上均优于三种基线方法。此外，我们评估了三种现有防御机制，发现它们对 CtrlRAG 的防御效果有限，凸显了开发更 robust 防御机制的迫切需求。

> Retrieval-Augmented Generation (RAG) systems enhance Large Language Models (LLMs) by integrating external knowledge bases. However, this integration introduces a new security threat: adversaries can exploit the retrieval mechanism to inject malicious content into the knowledge base, thereby influencing the generated responses. Based on this attack vector, we propose CtrlRAG, a novel attack method designed for RAG system in the black-box setting, which aligns with real-world scenarios. Unlike existing attack methods, CtrlRAG introduces a perturbation mechanism using Masked Language Model (MLM) to dynamically optimize malicious content in response to changes in the retrieved context. Experimental results demonstrate that CtrlRAG outperforms three baseline methods in both Emotional Manipulation and Hallucination Amplification objectives. Furthermore, we evaluate three existing defense mechanisms, revealing their limited effectiveness against CtrlRAG and underscoring the urgent need for more robust defenses.

[Arxiv](https://arxiv.org/abs/2503.06950)