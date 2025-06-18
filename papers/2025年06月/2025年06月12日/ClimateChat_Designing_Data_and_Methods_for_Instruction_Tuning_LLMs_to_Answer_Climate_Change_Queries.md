# ClimateChat: 为利用指令微调大型语言模型解答气候变化问题而设计数据与方法

发布时间：2025年06月12日

`LLM应用` `气候变化`

> ClimateChat: Designing Data and Methods for Instruction Tuning LLMs to Answer Climate Change Queries

# 摘要

> 随着全球气候变化问题日益严峻，气候科学研究的需求持续增长。以大型语言模型（LLMs）为代表的自然语言处理技术在气候变化领域得到了广泛应用，为决策者和公众提供关键信息支持。研究者通过构建气候变化相关指令数据并对LLMs进行指令微调，提升了模型性能。然而，现有研究在高效生成大量高精度气候变化指令数据方面仍存在局限，限制了气候变化LLMs的发展。本研究提出了一种自动化方法来构建指令数据，该方法利用文档中的事实和背景知识生成指令，并通过网络爬取和收集种子指令来增强数据多样性。我们据此构建了名为ClimateChat-Corpus的气候变化指令数据集，并用于微调开源LLMs，最终开发出名为ClimateChat的LLM。评估结果显示，ClimateChat在气候变化问答任务中表现显著提升。此外，我们还研究了不同基础模型和指令数据对LLM性能的影响，展示了其在适应多种气候变化科学发现任务方面的潜力，强调了选择合适基线模型进行指令微调的重要性。本研究为构建气候变化指令数据和训练特定领域LLMs提供了有价值的参考和实证支持。

> As the issue of global climate change becomes increasingly severe, the demand for research in climate science continues to grow. Natural language processing technologies, represented by Large Language Models (LLMs), have been widely applied to climate change-specific research, providing essential information support for decision-makers and the public. Some studies have improved model performance on relevant tasks by constructing climate change-related instruction data and instruction-tuning LLMs. However, current research remains inadequate in efficiently producing large volumes of high-precision instruction data for climate change, which limits further development of climate change LLMs. This study introduces an automated method for constructing instruction data. The method generates instructions using facts and background knowledge from documents and enhances the diversity of the instruction data through web scraping and the collection of seed instructions. Using this method, we constructed a climate change instruction dataset, named ClimateChat-Corpus, which was used to fine-tune open-source LLMs, resulting in an LLM named ClimateChat. Evaluation results show that ClimateChat significantly improves performance on climate change question-and-answer tasks. Additionally, we evaluated the impact of different base models and instruction data on LLM performance and demonstrated its capability to adapt to a wide range of climate change scientific discovery tasks, emphasizing the importance of selecting an appropriate base model for instruction tuning. This research provides valuable references and empirical support for constructing climate change instruction data and training climate change-specific LLMs.

[Arxiv](https://arxiv.org/abs/2506.13796)