# 抗体基础模型：Ab-RoBERTa

发布时间：2025年06月15日

`LLM应用` `生物技术` `抗体工程`

> Antibody Foundational Model : Ab-RoBERTa

# 摘要

> 基于抗体的疗法重要性日益凸显，抗体工程作为关键的研发领域受到广泛关注。基于transformer的蛋白质大语言模型（LLMs）在蛋白质序列设计和结构预测方面展现了巨大潜力。同时，OAS等大规模抗体数据库的出现为开发专门处理抗体序列的LLMs提供了新机遇。其中，RoBERTa相较于BERT性能更优，且参数量更小（1.25亿），相较于ProtBERT（4.20亿参数），这使其在抗体应用中更高效。然而，尽管RoBERTa架构优势明显，但基于其构建的特异性抗体基础模型尚未公开。为此，我们推出了Ab-RoBERTa，一款基于RoBERTa的特异性抗体大语言模型，现已开源，地址为https://huggingface.co/mogam-ai/Ab-RoBERTa。该模型旨在助力抗原结合位点预测、抗体人类化评估等广泛研究应用。

> With the growing prominence of antibody-based therapeutics, antibody engineering has gained increasing attention as a critical area of research and development. Recent progress in transformer-based protein large language models (LLMs) has demonstrated promising applications in protein sequence design and structural prediction. Moreover, the availability of large-scale antibody datasets such as the Observed Antibody Space (OAS) database has opened new avenues for the development of LLMs specialized for processing antibody sequences. Among these, RoBERTa has demonstrated improved performance relative to BERT, while maintaining a smaller parameter count (125M) compared to the BERT-based protein model, ProtBERT (420M). This reduced model size enables more efficient deployment in antibody-related applications. However, despite the numerous advantages of the RoBERTa architecture, antibody-specific foundational models built upon it have remained inaccessible to the research community. In this study, we introduce Ab-RoBERTa, a RoBERTa-based antibody-specific LLM, which is publicly available at https://huggingface.co/mogam-ai/Ab-RoBERTa. This resource is intended to support a wide range of antibody-related research applications including paratope prediction or humanness assessment.

[Arxiv](https://arxiv.org/abs/2506.13006)