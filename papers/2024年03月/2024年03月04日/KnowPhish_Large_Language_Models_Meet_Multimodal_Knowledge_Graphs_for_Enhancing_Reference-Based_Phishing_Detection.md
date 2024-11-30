# KnowPhish项目将大型语言模型与多模态知识图谱相结合，旨在强化基于参照的钓鱼检测技术，实现更高效的网络欺诈识别。

发布时间：2024年03月04日

`LLM应用`

> KnowPhish: Large Language Models Meet Multimodal Knowledge Graphs for Enhancing Reference-Based Phishing Detection

# 摘要

> 面对网络钓鱼攻击给用户和商家带来的重大损失，急需发展高效可靠的自动化检测技术。目前最前沿的方法是基于参考的网络钓鱼检测器（RBPD），它通过对比目标网页上的徽标与一组知名徽标来判断真伪。然而，现有的RBPD受限于依赖人工编制的品牌知识库，难以应对海量品牌，知识库的覆盖面不足导致易出现遗漏误判。针对此痛点，我们创新研发了一套自动化知识收集流程，并借此构建并公开了一个包含2万多个品牌的大型多模态品牌知识库——KnowPhish，内含丰富的各品牌详细信息。KnowPhish可以无缝对接现有RBPD，大幅提升其性能表现。此外，当前RBPD只关注图像模式识别，忽略了网页HTML中蕴含的有益文本信息。为此，我们运用大型语言模型（LLM）技术，设计了一种从文本中抽取出网页品牌信息的新方案。最终形成的多模态网络钓鱼检测工具——KnowPhish检测器（KPD），无论网页是否包含徽标，都能有效甄别钓鱼网页。我们在人工验证数据集及新加坡本地语境下进行了实地测试，结果表明，KnowPhish与KPD相较于现有的顶尖基准，在检测准确性和效率方面均取得了显著的进步。

> Phishing attacks have inflicted substantial losses on individuals and businesses alike, necessitating the development of robust and efficient automated phishing detection approaches. Reference-based phishing detectors (RBPDs), which compare the logos on a target webpage to a known set of logos, have emerged as the state-of-the-art approach. However, a major limitation of existing RBPDs is that they rely on a manually constructed brand knowledge base, making it infeasible to scale to a large number of brands, which results in false negative errors due to the insufficient brand coverage of the knowledge base. To address this issue, we propose an automated knowledge collection pipeline, using which we collect and release a large-scale multimodal brand knowledge base, KnowPhish, containing 20k brands with rich information about each brand. KnowPhish can be used to boost the performance of existing RBPDs in a plug-and-play manner. A second limitation of existing RBPDs is that they solely rely on the image modality, ignoring useful textual information present in the webpage HTML. To utilize this textual information, we propose a Large Language Model (LLM)-based approach to extract brand information of webpages from text. Our resulting multimodal phishing detection approach, KnowPhish Detector (KPD), can detect phishing webpages with or without logos. We evaluate KnowPhish and KPD on a manually validated dataset, and on a field study under Singapore's local context, showing substantial improvements in effectiveness and efficiency compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2403.02253)