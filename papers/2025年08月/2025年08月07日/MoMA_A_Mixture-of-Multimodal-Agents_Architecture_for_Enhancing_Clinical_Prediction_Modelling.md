# MoMA：一种多模态智能体混合架构，助力临床预测建模的优化

发布时间：2025年08月07日

`Agent`

> MoMA: A Mixture-of-Multimodal-Agents Architecture for Enhancing Clinical Prediction Modelling

# 摘要

> 多模态电子健康记录（EHR）数据相较于单一模态数据，能够为患者健康状况提供更加丰富且互补的洞察。然而，如何有效整合多种数据模态进行临床预测建模仍然面临挑战，主要源于数据需求量庞大。为此，我们提出了一种新型架构——多模态代理混合架构（MoMA），旨在利用多个大型语言模型（LLM）代理，结合多模态EHR数据进行临床预测任务。MoMA采用了专门的LLM代理（“专家代理”），将非文本模态（如医学影像和实验室结果）转换为结构化的文本摘要。这些摘要与临床笔记一同，由另一个LLM（“聚合代理”）整合生成统一的多模态摘要，随后由第三个LLM（“预测代理”）基于此摘要生成临床预测。通过在真实世界数据集上评估MoMA在不同模态组合和预测设置下的三项预测任务，结果显示MoMA超越了现有的最先进方法，凸显了其在各类任务中的更高准确性和灵活性。

> Multimodal electronic health record (EHR) data provide richer, complementary insights into patient health compared to single-modality data. However, effectively integrating diverse data modalities for clinical prediction modeling remains challenging due to the substantial data requirements. We introduce a novel architecture, Mixture-of-Multimodal-Agents (MoMA), designed to leverage multiple large language model (LLM) agents for clinical prediction tasks using multimodal EHR data. MoMA employs specialized LLM agents ("specialist agents") to convert non-textual modalities, such as medical images and laboratory results, into structured textual summaries. These summaries, together with clinical notes, are combined by another LLM ("aggregator agent") to generate a unified multimodal summary, which is then used by a third LLM ("predictor agent") to produce clinical predictions. Evaluating MoMA on three prediction tasks using real-world datasets with different modality combinations and prediction settings, MoMA outperforms current state-of-the-art methods, highlighting its enhanced accuracy and flexibility across various tasks.

[Arxiv](https://arxiv.org/abs/2508.05492)