# OpenReviewer：一个专门用于生成关键科学论文评论的大型语言模型

发布时间：2024年12月16日

`LLM应用` `机器学习` `会议论文评审`

> OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews

# 摘要

> 我们推出了 OpenReviewer 这一开源系统，它能够为机器学习和人工智能会议论文生成高品质的同行评审。其核心是 Llama-OpenReviewer-8B，这是一个拥有 8B 参数的语言模型，专门在来自顶级 ML 会议的 79,000 份专家评审上做了微调。当给定一份 PDF 论文提交和评审模板作为输入时，OpenReviewer 会提取包括方程和表格等在内的全文内容，并依照会议特定的指南生成结构化评审。我们对 400 篇测试论文的评估显示，与 GPT-4 和 Claude-3.5 等通用大型语言模型相比，OpenReviewer 生成的评审更具批判性和现实性。其他大型语言模型往往给出过于积极的评估，而 OpenReviewer 的建议与人类评审者的评分分布高度吻合。该系统能在作者提交之前为其提供快速且有建设性的反馈，以改进手稿，不过它并非要取代人类同行评审。OpenReviewer 有在线演示和开源工具可供使用。

> We present OpenReviewer, an open-source system for generating high-quality peer reviews of machine learning and AI conference papers. At its core is Llama-OpenReviewer-8B, an 8B parameter language model specifically fine-tuned on 79,000 expert reviews from top ML conferences. Given a PDF paper submission and review template as input, OpenReviewer extracts the full text, including technical content like equations and tables, and generates a structured review following conference-specific guidelines. Our evaluation on 400 test papers shows that OpenReviewer produces significantly more critical and realistic reviews compared to general-purpose LLMs like GPT-4 and Claude-3.5. While other LLMs tend toward overly positive assessments, OpenReviewer's recommendations closely match the distribution of human reviewer ratings. The system provides authors with rapid, constructive feedback to improve their manuscripts before submission, though it is not intended to replace human peer review. OpenReviewer is available as an online demo and open-source tool.

[Arxiv](https://arxiv.org/abs/2412.11948)