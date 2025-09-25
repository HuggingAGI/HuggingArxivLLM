# CON-QA：合同领域中基于云大型语言模型的隐私保护问答

发布时间：2025年09月24日

`LLM应用` `法律科技`

> CON-QA: Privacy-Preserving QA using cloud LLMs in Contract Domain

# 摘要

> 随着企业纷纷将ChatGPT、Gemini等云端大型语言模型（LLMs）融入法律文档处理流程，保护敏感合同信息（包括个人身份信息（PII）和商业敏感条款）已成为一项严峻挑战。为此，我们提出CON-QA——一个专为企业合同安全问答设计的混合隐私保护框架，巧妙融合本地部署与云端托管的LLMs。CON-QA框架通过三个阶段实现：（i）借助本地部署的LLM进行语义查询分解和查询感知的文档块检索；（ii）采用结构化一对多映射方案对检测到的敏感实体进行匿名化处理，在防止跨会话实体推理攻击的同时确保语义连贯；（iii）由云端LLM生成匿名化响应，并通过会话一致的多对一反向映射在本地准确还原原始答案。为全面评估CON-QA，我们构建了CUAD-QA语料库——基于510份真实CUAD合同文档生成的85k问答对集合，涵盖简单、复杂及摘要类查询。实证评估结合人工细致评测表明，CON-QA在隐私保护与实用价值间实现了有效平衡，既保证了答案质量和法律条款语义的准确性，又大幅降低了隐私风险，充分证明了其在企业级合同文档安全问答场景中的实用价值。

> As enterprises increasingly integrate cloud-based large language models (LLMs) such as ChatGPT and Gemini into their legal document workflows, protecting sensitive contractual information - including Personally Identifiable Information (PII) and commercially sensitive clauses - has emerged as a critical challenge. In this work, we propose CON-QA, a hybrid privacy-preserving framework designed specifically for secure question answering over enterprise contracts, effectively combining local and cloud-hosted LLMs. The CON-QA framework operates through three stages: (i) semantic query decomposition and query-aware document chunk retrieval using a locally deployed LLM analysis, (ii) anonymization of detected sensitive entities via a structured one-to-many mapping scheme, ensuring semantic coherence while preventing cross-session entity inference attacks, and (iii) anonymized response generation by a cloud-based LLM, with accurate reconstruction of the original answer locally using a session-consistent many-to-one reverse mapping. To rigorously evaluate CON-QA, we introduce CUAD-QA, a corpus of 85k question-answer pairs generated over 510 real-world CUAD contract documents, encompassing simple, complex, and summarization-style queries. Empirical evaluations, complemented by detailed human assessments, confirm that CON-QA effectively maintains both privacy and utility, preserves answer quality, maintains fidelity to legal clause semantics, and significantly mitigates privacy risks, demonstrating its practical suitability for secure, enterprise-level contract documents.

[Arxiv](https://arxiv.org/abs/2509.19925)