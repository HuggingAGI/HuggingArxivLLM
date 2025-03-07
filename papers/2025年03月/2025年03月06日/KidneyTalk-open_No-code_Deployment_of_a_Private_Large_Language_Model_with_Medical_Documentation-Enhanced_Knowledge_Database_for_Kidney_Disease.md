# # KidneyTalk-open：零代码部署的私人大型语言模型，内置增强医疗文档知识库，专为肾脏疾病量身打造

发布时间：2025年03月06日

`LLM应用` `问答系统`

> KidneyTalk-open: No-code Deployment of a Private Large Language Model with Medical Documentation-Enhanced Knowledge Database for Kidney Disease

# 摘要

> 肾脏疾病的隐私保护医疗决策支持需要在本地化部署大型语言模型（LLMs）的同时保持临床推理能力。当前解决方案面临三大挑战：1）基于云的LLMs存在数据安全风险；2）本地模型部署需要技术专业知识；3）通用LLMs缺乏整合医学知识的机制。检索增强系统在处理医学文档和临床可用性方面也存在困难。

我们开发了KidneyTalk-open，一个集成三项技术组件的桌面系统：1）通过本地推理引擎实现先进开源LLMs（如DeepSeek-r1，Qwen2.5）的无代码部署；2）结合上下文感知分块和智能过滤的医学文档处理流水线；3）采用智能体协作以提高医学文档召回率的自适应检索和增强流水线（AddRep）。设计了一个图形界面，使临床医生无需技术专业知识即可管理医学文档并进行AI增强的咨询。

在1,455道具有挑战性的肾脏病考试题目上的实验验证表明AddRep的有效性：通过智能知识整合实现了29.1%的准确率（较基线提升8.1%），并通过4.9%的拒绝率抑制幻觉，保持了鲁棒性。与主流产品（AnythingLLM，Chatbox，GPT4ALL）的比较案例研究证明了KidneyTalk-open在真实临床查询中的优越性能。

KidneyTalk-open代表了首个无代码医疗LLM系统，可在桌面上实现安全的文档增强型医疗问答。其设计为隐私敏感的临床AI应用建立了新框架。该系统显著降低了技术门槛，同时提高了证据可追溯性，使更多医疗人员或患者能够方便地使用先进的开源LLMs。

> Privacy-preserving medical decision support for kidney disease requires localized deployment of large language models (LLMs) while maintaining clinical reasoning capabilities. Current solutions face three challenges: 1) Cloud-based LLMs pose data security risks; 2) Local model deployment demands technical expertise; 3) General LLMs lack mechanisms to integrate medical knowledge. Retrieval-augmented systems also struggle with medical document processing and clinical usability. We developed KidneyTalk-open, a desktop system integrating three technical components: 1) No-code deployment of state-of-the-art (SOTA) open-source LLMs (such as DeepSeek-r1, Qwen2.5) via local inference engine; 2) Medical document processing pipeline combining context-aware chunking and intelligent filtering; 3) Adaptive Retrieval and Augmentation Pipeline (AddRep) employing agents collaboration for improving the recall rate of medical documents. A graphical interface was designed to enable clinicians to manage medical documents and conduct AI-powered consultations without technical expertise. Experimental validation on 1,455 challenging nephrology exam questions demonstrates AddRep's effectiveness: achieving 29.1% accuracy (+8.1% over baseline) with intelligent knowledge integration, while maintaining robustness through 4.9% rejection rate to suppress hallucinations. Comparative case studies with the mainstream products (AnythingLLM, Chatbox, GPT4ALL) demonstrate KidneyTalk-open's superior performance in real clinical query. KidneyTalk-open represents the first no-code medical LLM system enabling secure documentation-enhanced medical Q&A on desktop. Its designs establishes a new framework for privacy-sensitive clinical AI applications. The system significantly lowers technical barriers while improving evidence traceability, enabling more medical staff or patients to use SOTA open-source LLMs conveniently.

[Arxiv](https://arxiv.org/abs/2503.04153)