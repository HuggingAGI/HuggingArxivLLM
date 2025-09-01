# 这张图表在撒谎吗？实现误导性可视化的自动化检测

发布时间：2025年08月29日

`LLM应用` `媒体与娱乐`

> Is this chart lying to me? Automating the detection of misleading visualizations

# 摘要

> 误导性可视化是社交媒体与网络错误信息的重要推手。这类可视化通过违反图表设计原则扭曲数据，诱使读者得出错误结论。已有研究表明，人类和多模态大型语言模型（MLLMs）常被这类可视化误导。若能自动检测误导性可视化并识别其违反的具体设计规则，将有助于保护读者、减少错误信息传播。然而，由于缺乏大型、多样化且公开可用的数据集，AI模型的训练与评估一直受限。本研究中，我们引入了Misviz基准——含2604个真实世界可视化样本，并标注了12种误导类型。为支持模型训练，我们还发布了合成数据集Misviz-synth，该数据集基于真实数据表，用Matplotlib生成了81814个可视化样本。我们利用最先进的MLLMs、基于规则的系统及微调分类器，对两个数据集进行了全面评估。结果显示，该任务仍极具挑战性。目前，我们已公开Misviz、Misviz-synth及相关代码。

> Misleading visualizations are a potent driver of misinformation on social media and the web. By violating chart design principles, they distort data and lead readers to draw inaccurate conclusions. Prior work has shown that both humans and multimodal large language models (MLLMs) are frequently deceived by such visualizations. Automatically detecting misleading visualizations and identifying the specific design rules they violate could help protect readers and reduce the spread of misinformation. However, the training and evaluation of AI models has been limited by the absence of large, diverse, and openly available datasets. In this work, we introduce Misviz, a benchmark of 2,604 real-world visualizations annotated with 12 types of misleaders. To support model training, we also release Misviz-synth, a synthetic dataset of 81,814 visualizations generated using Matplotlib and based on real-world data tables. We perform a comprehensive evaluation on both datasets using state-of-the-art MLLMs, rule-based systems, and fine-tuned classifiers. Our results reveal that the task remains highly challenging. We release Misviz, Misviz-synth, and the accompanying code.

[Arxiv](https://arxiv.org/abs/2508.21675)