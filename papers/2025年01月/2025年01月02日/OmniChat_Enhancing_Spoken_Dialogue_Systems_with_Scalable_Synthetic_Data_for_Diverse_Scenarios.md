# OmniChat: 利用可扩展的合成数据，提升口语对话系统在多样化场景中的表现

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何利用合成数据来增强跨场景对话模型，并开发了一个多轮对话系统OmniChat。这涉及到大型语言模型在语音对话系统中的应用，特别是如何通过合成数据来优化对话系统的性能。因此，这篇论文应被归类为LLM应用。` `语音交互` `对话系统`

> OmniChat: Enhancing Spoken Dialogue Systems with Scalable Synthetic Data for Diverse Scenarios

# 摘要

> 随着大型语言模型的迅猛发展，研究人员开发出了越来越先进的语音对话系统，能够与人类自然交流。然而，这些系统仍难以应对现实对话的复杂性，如音频事件、音乐背景和情感表达，主要原因是现有对话数据集在规模和场景多样性上存在局限。本文提出利用合成数据来增强跨场景对话模型。我们推出了ShareChatX，首个涵盖多种场景的大规模语音对话数据集。基于此，我们开发了OmniChat，一个具备异构特征融合模块的多轮对话系统，旨在优化不同对话场景中的特征选择。此外，我们还探讨了使用合成数据训练对话系统的关键问题。通过大量实验，我们找到了合成数据与真实数据的最佳平衡，并在真实对话数据集DailyTalk上取得了领先成果。我们特别强调了合成数据在处理复杂对话场景（尤其是涉及音频和音乐的场景）中的重要性。更多详情，请访问我们的演示页面url{https://sharechatx.github.io/}。

> With the rapid development of large language models, researchers have created increasingly advanced spoken dialogue systems that can naturally converse with humans. However, these systems still struggle to handle the full complexity of real-world conversations, including audio events, musical contexts, and emotional expressions, mainly because current dialogue datasets are constrained in both scale and scenario diversity. In this paper, we propose leveraging synthetic data to enhance the dialogue models across diverse scenarios. We introduce ShareChatX, the first comprehensive, large-scale dataset for spoken dialogue that spans diverse scenarios. Based on this dataset, we introduce OmniChat, a multi-turn dialogue system with a heterogeneous feature fusion module, designed to optimize feature selection in different dialogue contexts. In addition, we explored critical aspects of training dialogue systems using synthetic data. Through comprehensive experimentation, we determined the ideal balance between synthetic and real data, achieving state-of-the-art results on the real-world dialogue dataset DailyTalk. We also highlight the crucial importance of synthetic data in tackling diverse, complex dialogue scenarios, especially those involving audio and music. For more details, please visit our demo page at url{https://sharechatx.github.io/}.

[Arxiv](https://arxiv.org/abs/2501.01384)