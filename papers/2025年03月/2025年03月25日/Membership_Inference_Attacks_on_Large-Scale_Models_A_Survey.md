# 大型模型的成员推断攻击研究综述

发布时间：2025年03月25日

`LLM应用` `人工智能`

> Membership Inference Attacks on Large-Scale Models: A Survey

# 摘要

> 自2022年11月OpenAI的ChatGPT上线以来，大型语言模型（LLM）的应用呈爆发式增长。与此同时，能够处理多种数据类型并通过不同渠道实现交互的大型多模态模型（LMMs）也取得了突破性进展，成功打破了早期LLMs仅限于文本到文本的限制，吸引了学术界和产业界的双重关注。然而，随着LLMs和LMMs的广泛应用，隐私风险问题日益凸显。成员推断攻击（MIAs）作为一种判断特定数据点是否曾参与模型训练的技术，已成为衡量机器学习模型隐私漏洞的重要指标。Hu等人研究表明，多种机器学习算法都可能遭受MIAs的攻击。尽管传统模型上的MIAs研究已较为成熟，但针对现代大规模模型（如LLMs和LMMs）的系统性研究仍显不足，特别是在其实际效果及潜在影响方面。本文系统性地梳理了近期针对LLMs和LMMs的MIA研究进展，基于攻击方法和应用场景对各类攻击进行了深入分析和分类，并指出了现有研究的不足之处。此外，我们还探讨了模型微调过程中的隐私风险问题。最后，本文为未来在此领域的研究方向提供了若干建议。

> The adoption of the Large Language Model (LLM) has accelerated dramatically since the ChatGPT from OpenAI went online in November 2022. Recent advances in Large Multimodal Models (LMMs), which process diverse data types and enable interaction through various channels, have expanded beyond the text-to-text limitations of early LLMs, attracting significant and concurrent attention from both researchers and industry. While LLMs and LMMs are starting to spread widely, concerns about their privacy risks are increasing as well. Membership Inference Attacks (MIAs), techniques used to determine whether a particular data point was part of a model's training set, serve as a key metric for assessing the privacy vulnerabilities of machine learning models. Hu et al. show that various machine learning algorithms are vulnerable to MIA. Despite extensive studies on MIAs in traditional models, there remains a lack of systematic surveys addressing their effectiveness and implications in modern large-scale models like LLMs and LMMs. In this paper, we systematically reviewed recent studies of MIA against LLMs and LMMs. We analyzed and categorized each attack based on their methodology and scenario and discussed the limitations in existing research. Additionally, we examine privacy concerns associated with the fine-tuning process. Finally, we provided some suggestions for future research in this direction.

[Arxiv](https://arxiv.org/abs/2503.19338)