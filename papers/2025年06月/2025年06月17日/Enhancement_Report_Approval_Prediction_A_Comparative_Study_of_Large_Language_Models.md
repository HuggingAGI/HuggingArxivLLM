# 增强报告审批预测：大型语言模型的对比研究

发布时间：2025年06月17日

`LLM应用` `软件开发` `软件工程`

> Enhancement Report Approval Prediction: A Comparative Study of Large Language Models

# 摘要

> 增强报告（ERs）是连接用户与开发者的桥梁，承载着软件优化的金点子。然而，手动处理这些报告耗时费力，容易错失宝贵见解。为解决这一难题，增强报告审批预测（ERAP）应运而生，借助机器学习技术实现决策自动化。尽管传统方法依赖基于特征的分类器和深度学习模型，但大型语言模型（LLM）的突破为提升预测精度开辟了新途径。本研究对比了18种LLM变体（包括BERT、RoBERTa、DeBERTa-v3、ELECTRA和XLNet等编码器模型；GPT-3.5-turbo、GPT-4o-mini、Llama 3.1 8B、Llama 3.1 8B Instruct和DeepSeek-V3等解码器模型）与传统方法（CNN/LSTM-BERT/GloVe）。实验结果令人振奋：（1）引入创建者档案使未微调的解码器模型准确率跃升10.8%，尽管可能伴随偏差；（2）经过LoRA微调的Llama 3.1 8B Instruct表现更优，准确率达到79%，已批准报告的召回率更是高达76.1%（远超LSTM-GLOVE的64.1%），在严格的时间顺序评估中比传统方法高出5%，并有效缓解了类别不平衡问题。这些成果彰显了LLM在ERAP中的卓越实力，预示着其在优化软件维护流程和提升真实开发环境决策效能的广阔前景。此外，我们深入分析了大型模型表现欠佳的ER案例，为未来研究指明了方向。

> Enhancement reports (ERs) serve as a critical communication channel between users and developers, capturing valuable suggestions for software improvement. However, manually processing these reports is resource-intensive, leading to delays and potential loss of valuable insights. To address this challenge, enhancement report approval prediction (ERAP) has emerged as a research focus, leveraging machine learning techniques to automate decision-making. While traditional approaches have employed feature-based classifiers and deep learning models, recent advancements in large language models (LLM) present new opportunities for enhancing prediction accuracy. This study systematically evaluates 18 LLM variants (including BERT, RoBERTa, DeBERTa-v3, ELECTRA, and XLNet for encoder models; GPT-3.5-turbo, GPT-4o-mini, Llama 3.1 8B, Llama 3.1 8B Instruct and DeepSeek-V3 for decoder models) against traditional methods (CNN/LSTM-BERT/GloVe). Our experiments reveal two key insights: (1) Incorporating creator profiles increases unfine-tuned decoder-only models' overall accuracy by 10.8 percent though it may introduce bias; (2) LoRA fine-tuned Llama 3.1 8B Instruct further improve performance, reaching 79 percent accuracy and significantly enhancing recall for approved reports (76.1 percent vs. LSTM-GLOVE's 64.1 percent), outperforming traditional methods by 5 percent under strict chronological evaluation and effectively addressing class imbalance issues. These findings establish LLM as a superior solution for ERAP, demonstrating their potential to streamline software maintenance workflows and improve decision-making in real-world development environments. We also investigated and summarized the ER cases where the large models underperformed, providing valuable directions for future research.

[Arxiv](https://arxiv.org/abs/2506.15098)