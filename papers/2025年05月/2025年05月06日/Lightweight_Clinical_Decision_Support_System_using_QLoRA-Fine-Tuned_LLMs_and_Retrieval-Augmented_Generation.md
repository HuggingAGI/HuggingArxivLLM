# 基于 QLoRA 微调 LLM 与检索增强生成的轻量级临床决策支持系统

发布时间：2025年05月06日

`RAG` `医疗决策支持`

> Lightweight Clinical Decision Support System using QLoRA-Fine-Tuned LLMs and Retrieval-Augmented Generation

# 摘要

> 本文探讨了大型语言模型（LLMs）在医疗领域的应用，重点关注通过检索增强生成（RAG）结合医院特定数据以及量化低秩适配（QLoRA）微调来提升医疗决策支持能力。我们采用Llama 3.2-3B-Instruct作为基础模型，通过嵌入和检索相关医疗信息，显著提升了系统响应的准确性。QLoRA不仅实现了参数效率和内存优化，还通过量化技术保障了医疗信息的完整性。研究结果表明，我们的模型在多个医疗基准测试中表现优异，能够提供基础医疗建议。本文详细介绍了系统的架构、量化方法及其关键应用，包括基于患者症状和病史的疾病预测、治疗建议以及复杂医疗报告的高效总结。同时，我们探讨了患者隐私、数据安全、临床验证等伦理问题，以及实际部署中的挑战。轻量化量化权重设计使该系统在资源有限的医院环境中也能轻松部署和扩展。最后，本文分析了LLMs对医疗保健的深远影响，并展望了其在医疗领域的未来发展方向。

> This research paper investigates the application of Large Language Models (LLMs) in healthcare, specifically focusing on enhancing medical decision support through Retrieval-Augmented Generation (RAG) integrated with hospital-specific data and fine-tuning using Quantized Low-Rank Adaptation (QLoRA). The system utilizes Llama 3.2-3B-Instruct as its foundation model. By embedding and retrieving context-relevant healthcare information, the system significantly improves response accuracy. QLoRA facilitates notable parameter efficiency and memory optimization, preserving the integrity of medical information through specialized quantization techniques. Our research also shows that our model performs relatively well on various medical benchmarks, indicating that it can be used to make basic medical suggestions. This paper details the system's technical components, including its architecture, quantization methods, and key healthcare applications such as enhanced disease prediction from patient symptoms and medical history, treatment suggestions, and efficient summarization of complex medical reports. We touch on the ethical considerations-patient privacy, data security, and the need for rigorous clinical validation-as well as the practical challenges of integrating such systems into real-world healthcare workflows. Furthermore, the lightweight quantized weights ensure scalability and ease of deployment even in low-resource hospital environments. Finally, the paper concludes with an analysis of the broader impact of LLMs on healthcare and outlines future directions for LLMs in medical settings.

[Arxiv](https://arxiv.org/abs/2505.03406)