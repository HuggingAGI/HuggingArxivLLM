# 大型开源项目中的自动化缺陷报告优先级排序

发布时间：2025年04月22日

`LLM应用` `软件工程` `缺陷管理`

> Automated Bug Report Prioritization in Large Open-Source Projects

# 摘要

> 大型开源项目每天接收来自用户和开发人员社区的大量问题，包括软件缺陷报告和新功能请求。由于资源有限，项目无法处理所有问题，因此需要根据优先级和严重性对问题进行排序。本文提出了一种基于缺陷报告自然语言文本的自动化缺陷优先级分配方法，这些文本存储在问题跟踪系统中的开放缺陷存储库中。我们采用TopicMiner-MTM主题建模方法和BERT大型语言模型进行文本分类，实验结果表明，与现有方法相比，我们在准确率、精确率、召回率和F1度量方面均取得了更好的效果。使用包含Eclipse Platform项目85,156个缺陷报告的参考数据集进行的实验验证了这一结论。

> Large open-source projects receive a large number of issues (known as bugs), including software defect (i.e., bug) reports and new feature requests from their user and developer communities at a fast rate. The often limited project resources do not allow them to deal with all issues. Instead, they have to prioritize them according to the project's priorities and the issues' severities. In this paper, we propose a novel approach to automated bug prioritization based on the natural language text of the bug reports that are stored in the open bug repositories of the issue-tracking systems. We conduct topic modeling using a variant of LDA called TopicMiner-MTM and text classification with the BERT large language model to achieve a higher performance level compared to the state-of-the-art. Experimental results using an existing reference dataset containing 85,156 bug reports of the Eclipse Platform project indicate that we outperform existing approaches in terms of Accuracy, Precision, Recall, and F1-measure of the bug report priority prediction.

[Arxiv](https://arxiv.org/abs/2504.15912)