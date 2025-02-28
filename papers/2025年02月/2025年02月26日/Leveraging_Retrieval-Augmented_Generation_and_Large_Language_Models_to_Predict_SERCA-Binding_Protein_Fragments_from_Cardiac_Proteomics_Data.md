# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月26日

`LLM应用` `蛋白质组学` `生物信息学`

> Leveraging Retrieval-Augmented Generation and Large Language Models to Predict SERCA-Binding Protein Fragments from Cardiac Proteomics Data

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域表现卓越，其应用已拓展至蛋白质组学领域，特别是用于分类蛋白片段。本研究聚焦于心肌细胞中与内质网相关的蛋白片段，构建了一个包含数千个蛋白片段的质谱数据集。部分蛋白片段已通过克隆和表征研究其对内质网钙泵SERCA的影响。基于此数据集，我们探索了仅凭蛋白片段的序列及其生物物理特性（如疏水性）能否通过LLMs准确预测其与SERCA的结合能力。研究中，我们基于已克隆的片段生成随机序列，将其嵌入检索增强生成（RAG）数据库并按相似性分组，随后微调LLM提示以预测新序列与SERCA的结合可能性。我们采用Meta/llama系列等开源LLMs及Huggingface仓库中的嵌入函数进行基准测试。进一步，我们评估了该方法在分类未克隆表征的新型质谱蛋白片段方面的泛化能力。通过优化提示以纳入内质网滞留序列等基序，我们显著提升了分类准确度，并识别出核糖体蛋白L2和硒蛋白S等预测定位于内质网且能结合SERCA的蛋白质。尽管研究数据源自心肌细胞，但本方法凸显了LLMs在有限蛋白质组学数据下发现新型蛋白质相互作用和功能的潜力。

> Large language models (LLMs) have shown promise in various natural language processing tasks, including their application to proteomics data to classify protein fragments. In this study, we curated a limited mass spectrometry dataset with 1000s of protein fragments, consisting of proteins that appear to be attached to the endoplasmic reticulum in cardiac cells, of which a fraction was cloned and characterized for their impact on SERCA, an ER calcium pump. With this limited dataset, we sought to determine whether LLMs could correctly predict whether a new protein fragment could bind SERCA, based only on its sequence and a few biophysical characteristics, such as hydrophobicity, determined from that sequence. To do so, we generated random sequences based on cloned fragments, embedded the fragments into a retrieval augmented generation (RAG) database to group them by similarity, then fine-tuned large language model (LLM) prompts to predict whether a novel sequence could bind SERCA. We benchmarked this approach using multiple open-source LLMs, namely the Meta/llama series, and embedding functions commonly available on the Huggingface repository. We then assessed the generalizability of this approach in classifying novel protein fragments from mass spectrometry that were not initially cloned for functional characterization. By further tuning the prompt to account for motifs, such as ER retention sequences, we improved the classification accuracy by and identified several proteins predicted to localize to the endoplasmic reticulum and bind SERCA, including Ribosomal Protein L2 and selenoprotein S. Although our results were based on proteomics data from cardiac cells, our approach demonstrates the potential of LLMs in identifying novel protein interactions and functions with very limited proteomic data.

[Arxiv](https://arxiv.org/abs/2502.19574)