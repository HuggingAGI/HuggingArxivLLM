# # 通过隐蔽检索器投毒禁用检索增强生成的自校正

发布时间：2025年08月27日

`RAG` `基础理论`

> Disabling Self-Correction in Retrieval-Augmented Generation via Stealthy Retriever Poisoning

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型（LLMs）可靠性的标准方案。以往研究表明，通过污染知识库可误导RAG系统生成攻击者指定的输出，从而暴露其脆弱性。但本文发现，现代LLMs具备强大的自校正能力（SCA）——若配置得当，便能识别并拒绝虚假上下文，进而缓解此类攻击。这种SCA为意图操纵RAG系统的攻击者带来了严峻挑战。
  与以往主要针对知识库的投毒方法不同，我们提出了	extsc{DisarmRAG}——一种全新的投毒范式，它通过破坏检索器本身来抑制SCA，并强制生成攻击者指定的输出。这种破坏使攻击者能直接将反SCA指令嵌入生成器的输入上下文中，从而绕过SCA。为此，我们研发了一种基于对比学习的模型编辑技术，可实现局部且隐蔽的编辑：确保检索器仅对特定受害查询返回恶意指令，同时维持正常查询的良性检索行为。为进一步强化攻击效果，我们设计了迭代协同优化框架，能自动发现可绕过基于提示防御的稳健指令。我们在六个LLM和三个QA基准上对DisarmRAG展开全面评估，结果显示：恶意指令的检索成功率近乎完美，不仅成功抑制了SCA，在各类防御性提示下攻击成功率均超90%。此外，经编辑的检索器在多种检测方法下仍能保持隐蔽，这凸显了构建以检索器为核心的防御机制的迫切性。

> Retrieval-Augmented Generation (RAG) has become a standard approach for improving the reliability of large language models (LLMs). Prior work demonstrates the vulnerability of RAG systems by misleading them into generating attacker-chosen outputs through poisoning the knowledge base. However, this paper uncovers that such attacks could be mitigated by the strong \textit{self-correction ability (SCA)} of modern LLMs, which can reject false context once properly configured. This SCA poses a significant challenge for attackers aiming to manipulate RAG systems.
  In contrast to previous poisoning methods, which primarily target the knowledge base, we introduce \textsc{DisarmRAG}, a new poisoning paradigm that compromises the retriever itself to suppress the SCA and enforce attacker-chosen outputs. This compromisation enables the attacker to straightforwardly embed anti-SCA instructions into the context provided to the generator, thereby bypassing the SCA. To this end, we present a contrastive-learning-based model editing technique that performs localized and stealthy edits, ensuring the retriever returns a malicious instruction only for specific victim queries while preserving benign retrieval behavior. To further strengthen the attack, we design an iterative co-optimization framework that automatically discovers robust instructions capable of bypassing prompt-based defenses. We extensively evaluate DisarmRAG across six LLMs and three QA benchmarks. Our results show near-perfect retrieval of malicious instructions, which successfully suppress SCA and achieve attack success rates exceeding 90\% under diverse defensive prompts. Also, the edited retriever remains stealthy under several detection methods, highlighting the urgent need for retriever-centric defenses.

[Arxiv](https://arxiv.org/abs/2508.20083)