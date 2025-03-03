# 优化大型语言模型在金融文本中检测ESG活动的方法

发布时间：2025年02月28日

`LLM应用`

> Optimizing Large Language Models for ESG Activity Detection in Financial Texts

# 摘要

> 将环境、社会和治理（ESG）因素纳入企业决策是可持续金融的核心。然而，如何确保商业实践与不断变化的监管要求保持一致仍是当前一大挑战。AI驱动的解决方案可以通过自动评估可持续报告和非财务信息披露与特定ESG活动的一致性，为这一过程提供重要支持。然而，受限于通用大型语言模型（LLMs）在特定领域应用中的局限性以及高质量结构化数据的匮乏，这一任务依然充满挑战。本文研究了当前一代LLMs识别环境相关文本的能力，并证明通过结合原始数据和合成数据进行微调，能够显著提升模型性能。为此，我们推出了ESG-Activities基准数据集，包含1,325个标注文本段，依据欧盟ESG分类法进行分类。实验结果显示，在ESG-Activities数据集上进行微调可显著提高分类准确率，开源模型如Llama 7B和Gemma 7B在特定配置下甚至超越了大型专有解决方案。这些发现对金融分析师、政策制定者和AI研究人员具有重要意义，为通过先进自然语言处理技术提升ESG透明度和合规性提供了新思路。
    

> The integration of Environmental, Social, and Governance (ESG) factors into corporate decision-making is a fundamental aspect of sustainable finance. However, ensuring that business practices align with evolving regulatory frameworks remains a persistent challenge. AI-driven solutions for automatically assessing the alignment of sustainability reports and non-financial disclosures with specific ESG activities could greatly support this process. Yet, this task remains complex due to the limitations of general-purpose Large Language Models (LLMs) in domain-specific contexts and the scarcity of structured, high-quality datasets. In this paper, we investigate the ability of current-generation LLMs to identify text related to environmental activities. Furthermore, we demonstrate that their performance can be significantly enhanced through fine-tuning on a combination of original and synthetically generated data. To this end, we introduce ESG-Activities, a benchmark dataset containing 1,325 labelled text segments classified according to the EU ESG taxonomy. Our experimental results show that fine-tuning on ESG-Activities significantly enhances classification accuracy, with open models such as Llama 7B and Gemma 7B outperforming large proprietary solutions in specific configurations. These findings have important implications for financial analysts, policymakers, and AI researchers seeking to enhance ESG transparency and compliance through advanced natural language processing techniques.

[Arxiv](https://arxiv.org/abs/2502.21112)