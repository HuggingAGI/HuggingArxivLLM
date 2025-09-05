# 增强RAG的技术文档检索

发布时间：2025年09月04日

`RAG` `工业与制造`

> Enhancing Technical Documents Retrieval for RAG

# 摘要

> 本文提出了Technical-Embeddings——一个旨在优化技术文档语义检索的创新框架，适用于软硬件开发领域。我们的方法借助大型语言模型（LLMs）的能力，解决了复杂技术内容的理解与检索难题。首先，通过生成扩展表示来增强用户查询，这种表示能更精准地捕捉用户意图并提升数据集多样性，进而丰富嵌入模型的微调过程。其次，运用摘要提取技术对关键上下文信息进行编码，优化技术文档的表示效果。为进一步提升检索性能，我们采用软提示技术微调双编码器BERT模型，为查询和文档上下文设置独立的学习参数，以捕捉细粒度的语义差异。我们在RAG-EDA和Rust-Docs-QA两个公开数据集上对该方法进行了评估，结果显示Technical-Embeddings在精确率和召回率上均显著优于基线模型。研究结果表明，整合查询扩展与上下文摘要技术可有效增强技术领域的信息获取与理解能力。这项研究推动了检索增强生成（RAG）系统的发展，为工程和产品开发工作流中高效准确的技术文档检索开辟了新路径。

> In this paper, we introduce Technical-Embeddings, a novel framework designed to optimize semantic retrieval in technical documentation, with applications in both hardware and software development. Our approach addresses the challenges of understanding and retrieving complex technical content by leveraging the capabilities of Large Language Models (LLMs). First, we enhance user queries by generating expanded representations that better capture user intent and improve dataset diversity, thereby enriching the fine-tuning process for embedding models. Second, we apply summary extraction techniques to encode essential contextual information, refining the representation of technical documents. To further enhance retrieval performance, we fine-tune a bi-encoder BERT model using soft prompting, incorporating separate learning parameters for queries and document context to capture fine-grained semantic nuances. We evaluate our approach on two public datasets, RAG-EDA and Rust-Docs-QA, demonstrating that Technical-Embeddings significantly outperforms baseline models in both precision and recall. Our findings highlight the effectiveness of integrating query expansion and contextual summarization to enhance information access and comprehension in technical domains. This work advances the state of Retrieval-Augmented Generation (RAG) systems, offering new avenues for efficient and accurate technical document retrieval in engineering and product development workflows.

[Arxiv](https://arxiv.org/abs/2509.04139)