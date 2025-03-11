# # 策略：非结构化文本中的政治声明分割与标注策略

发布时间：2025年03月10日

`LLM应用` `政治学`

> Strategies for political-statement segmentation and labelling in unstructured text

# 摘要

> 议会演讲和政党宣言分析已成为计算政治文本研究的重要领域。尽管无监督方法在演讲分析中占据主导地位，但MARPOR项目的参与者已构建了一个带有逐条政治立场标签的宣言语料库。最近研究表明，这些标签可以通过神经模型进行预测；然而，现有方法依赖于给定的语句边界，限制了其跨领域应用。在本研究中，我们提出并测试了一系列统一的分割与分类框架——基于线性链CRFs、微调的文本到文本模型，以及结合上下文学习与约束解码的方法——这些框架可用于从原始文本数据中同时分割和分类语句。我们的方法在政治宣言的原始文本上实现了具有竞争力的准确率，并通过将其应用于英国下议院的记录，展示了其研究潜力，进而追踪过去三十年四大政党在政治上的发展轨迹。

> Analysis of parliamentary speeches and political-party manifestos has become an integral area of computational study of political texts. While speeches have been overwhelmingly analysed using unsupervised methods, a large corpus of manifestos with by-statement political-stance labels has been created by the participants of the MARPOR project. It has been recently shown that these labels can be predicted by a neural model; however, the current approach relies on provided statement boundaries, limiting out-of-domain applicability. In this work, we propose and test a range of unified split-and-label frameworks -- based on linear-chain CRFs, fine-tuned text-to-text models, and the combination of in-context learning with constrained decoding -- that can be used to jointly segment and classify statements from raw textual data. We show that our approaches achieve competitive accuracy when applied to raw text of political manifestos, and then demonstrate the research potential of our method by applying it to the records of the UK House of Commons and tracing the political trajectories of four major parties in the last three decades.

[Arxiv](https://arxiv.org/abs/2503.07179)