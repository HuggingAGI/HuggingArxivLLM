# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年08月06日

`LLM应用` `学术研究` `文献管理`

> A Reproducible, Scalable Pipeline for Synthesizing Autoregressive Model Literature

# 摘要

> 面对自回归生成模型研究的井喷式发展，我们开发了一个完全开源且可复现的解决方案。该系统能够自动从公开仓库中检索、筛选、提取、聚类和总结相关文献，并生成实验复现脚本。在50篇人工标注论文上，我们的模型实现了超过0.85的F1分数。实验证明，该系统在1000篇论文规模下具备良好的扩展性。通过三个经典案例研究——WikiText-2上的AWD-LSTM、WikiText-103上的Transformer-XL以及Lakh MIDI数据集上的自回归音乐模型——我们证实了该系统的复现能力，其测试困惑度与原始报告高度一致，误差仅在1-3%之间。

> The accelerating pace of research on autoregressive generative models has produced thousands of papers, making manual literature surveys and reproduction studies increasingly impractical. We present a fully open-source, reproducible pipeline that automatically retrieves candidate documents from public repositories, filters them for relevance, extracts metadata, hyper-parameters and reported results, clusters topics, produces retrieval-augmented summaries and generates containerised scripts for re-running selected experiments. Quantitative evaluation on 50 manually-annotated papers shows F1 scores above 0.85 for relevance classification, hyper-parameter extraction and citation identification. Experiments on corpora of up to 1000 papers demonstrate near-linear scalability with eight CPU workers. Three case studies -- AWD-LSTM on WikiText-2, Transformer-XL on WikiText-103 and an autoregressive music model on the Lakh MIDI dataset -- confirm that the extracted settings support faithful reproduction, achieving test perplexities within 1--3% of the original reports.

[Arxiv](https://arxiv.org/abs/2508.04612)