# MMORE：大规模多模态开放RAG与提取

发布时间：2025年09月15日

`RAG` `医疗健康`

> MMORE: Massive Multimodal Open RAG & Extraction

# 摘要

> 我们推出MMORE——一个用于大规模多模态开放检索增强生成与提取的开源工具链，旨在高效处理海量异构文档，实现知识的摄取、转换与检索。MMORE支持文本、表格、图像、邮件、音频、视频等15种以上文件类型，能将其统一处理为标准格式，为LLM下游应用提供支持。其架构采用模块化分布式处理设计，可跨CPU和GPU实现高效并行扩展。基准测试显示，MMORE处理速度较单节点基线提升3.8倍，扫描PDF处理准确率较Docling高出40%。工具链还集成混合密集-稀疏检索技术，同时支持交互式API调用与批量RAG端点服务。在PubMedQA数据集上的测试表明，经MMORE增强的医疗LLM能通过加深检索深度，显著提升生物医学问答（QA）的准确率。MMORE为在多样化现实场景的多模态数据中部署通用RAG系统奠定了坚实且可扩展的基础。项目代码已开源，地址为https://github.com/swiss-ai/mmore。

> We introduce MMORE, an open-source pipeline for Massive Multimodal Open RetrievalAugmented Generation and Extraction, designed to ingest, transform, and retrieve knowledge from heterogeneous document formats at scale. MMORE supports more than fifteen file types, including text, tables, images, emails, audio, and video, and processes them into a unified format to enable downstream applications for LLMs. The architecture offers modular, distributed processing, enabling scalable parallelization across CPUs and GPUs. On processing benchmarks, MMORE demonstrates a 3.8-fold speedup over single-node baselines and 40% higher accuracy than Docling on scanned PDFs. The pipeline integrates hybrid dense-sparse retrieval and supports both interactive APIs and batch RAG endpoints. Evaluated on PubMedQA, MMORE-augmented medical LLMs improve biomedical QA accuracy with increasing retrieval depth. MMORE provides a robust, extensible foundation for deploying task-agnostic RAG systems on diverse, real-world multimodal data. The codebase is available at https://github.com/swiss-ai/mmore.

[Arxiv](https://arxiv.org/abs/2509.11937)