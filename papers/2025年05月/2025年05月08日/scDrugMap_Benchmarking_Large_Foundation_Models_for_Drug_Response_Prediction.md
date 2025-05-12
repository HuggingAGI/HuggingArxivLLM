# # scDrugMap：大型基础模型在药物反应预测中的基准测试

发布时间：2025年05月08日

`LLM应用` `癌症治疗` `药物研发`

> scDrugMap: Benchmarking Large Foundation Models for Drug Response Prediction

# 摘要

> 药物耐药性是癌症治疗中的重大挑战。单细胞分析揭示了细胞异质性，但将大型基础模型应用于单细胞数据以预测药物反应仍处于探索阶段。我们开发了scDrugMap，一个集成了Python命令行界面和网络服务器的框架，用于药物反应预测。该框架评估了八种单细胞模型和两种大型语言模型，使用了包含326,000多个细胞（主集）和18,800个细胞（验证集）的整理数据集，覆盖36个数据集和多种组织及癌症类型。我们在合并数据和跨数据设置下进行了基准测试，采用层冻结和低秩适应（LoRA）微调策略。在合并数据情况下，scFoundation表现最佳，平均F1分数分别为0.971（层冻结）和0.947（微调），远超最低性能模型50%。在跨数据设置中，UCE微调后表现优异（平均F1：0.774），而scGPT在零样本学习中领先（平均F1：0.858）。总体而言，scDrugMap为单细胞数据中的药物反应预测提供了首个大规模基础模型基准测试，并作为一个用户友好、灵活的平台，助力药物发现和转化研究。

> Drug resistance presents a major challenge in cancer therapy. Single cell profiling offers insights into cellular heterogeneity, yet the application of large-scale foundation models for predicting drug response in single cell data remains underexplored. To address this, we developed scDrugMap, an integrated framework featuring both a Python command-line interface and a web server for drug response prediction. scDrugMap evaluates a wide range of foundation models, including eight single-cell models and two large language models, using a curated dataset of over 326,000 cells in the primary collection and 18,800 cells in the validation set, spanning 36 datasets and diverse tissue and cancer types. We benchmarked model performance under pooled-data and cross-data evaluation settings, employing both layer freezing and Low-Rank Adaptation (LoRA) fine-tuning strategies. In the pooled-data scenario, scFoundation achieved the best performance, with mean F1 scores of 0.971 (layer freezing) and 0.947 (fine-tuning), outperforming the lowest-performing model by over 50%. In the cross-data setting, UCE excelled post fine-tuning (mean F1: 0.774), while scGPT led in zero-shot learning (mean F1: 0.858). Overall, scDrugMap provides the first large-scale benchmark of foundation models for drug response prediction in single-cell data and serves as a user-friendly, flexible platform for advancing drug discovery and translational research.

[Arxiv](https://arxiv.org/abs/2505.05612)