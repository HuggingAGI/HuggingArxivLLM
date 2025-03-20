# # SPADE：面向机器生成文本检测的系统性对话扩展提示框架

发布时间：2025年03月19日

`LLM应用` `客户服务`

> SPADE: Systematic Prompt Framework for Automated Dialogue Expansion in Machine-Generated Text Detection

# 摘要

> 随着大型语言模型（LLMs）生成合成内容能力的提升，对其滥用的担忧日益加剧，推动了机器生成文本（MGT）检测模型的发展。然而，由于缺乏系统生成的高质量训练数据集，这些检测器面临巨大挑战。为解决这一问题，我们提出了一种基于结构化提示方法的合成用户对话生成的五个新颖数据增强框架，降低了传统数据收集方法的成本。我们的方法生成了14个新的对话数据集，并将其与七种MGT检测模型进行了基准测试。实验结果表明，使用我们提出的增强框架生成的混合数据集，检测性能有所提升。此外，考虑到现实中的代理无法预知对手未来的utterances，我们模拟了在线对话检测，研究了聊天历史长度与检测准确率的关系。我们还在我们的框架上评估了有限聊天历史下的在线检测性能。我们的开源数据集可以从https://github.com/AngieYYF/SPADE-customer-service-dialogue下载。

> The increasing capability of large language models (LLMs) to generate synthetic content has heightened concerns about their misuse, driving the development of Machine-Generated Text (MGT) detection models. However, these detectors face significant challenges due to the lack of systematically generated, high-quality datasets for training. To address this issue, we propose five novel data augmentation frameworks for synthetic user dialogue generation through a structured prompting approach, reducing the costs associated with traditional data collection methods. Our proposed method yields 14 new dialogue datasets, which we benchmark against seven MGT detection models. The results demonstrate improved generalization performance when utilizing a mixed dataset produced by our proposed augmentation framework. Furthermore, considering that real-world agents lack knowledge of future opponent utterances, we simulate online dialogue detection and examine the relationship between chat history length and detection accuracy. We also benchmark online detection performance with limited chat history on our frameworks. Our open-source datasets can be downloaded from https://github.com/AngieYYF/SPADE-customer-service-dialogue.

[Arxiv](https://arxiv.org/abs/2503.15044)