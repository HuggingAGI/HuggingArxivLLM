# 可解释的面部反欺骗：利用多模态大模型提升泛化能力

发布时间：2025年01月03日

`LLM应用

理由：这篇论文提出了一种基于多模态大语言模型（MLLM）的面部反欺诈（FAS）框架，将FAS任务转化为可解释的视觉问答（VQA）范式。论文中提到的“多模态大语言模型”和“视觉问答”都是典型的LLM应用场景，因此将其分类为LLM应用。` `面部识别`

> Interpretable Face Anti-Spoofing: Enhancing Generalization with Multimodal Large Language Models

# 摘要

> # 摘要
面部反欺诈（FAS）是保障面部识别系统安全与可靠的关键。现有FAS方法多为二分类任务，虽提供置信度分数，却缺乏解释性，且在域外场景（如新环境或未知欺诈类型）中泛化能力有限。为此，我们提出了一种基于多模态大语言模型（MLLM）的FAS框架——可解释面部反欺诈（I-FAS），将FAS任务转化为可解释的视觉问答（VQA）范式。具体而言，我们设计了欺诈感知标注与过滤（SCF）策略，为FAS图像生成高质量标注，通过自然语言解释增强模型监督。为减少训练中噪声标注的影响，我们开发了偏置语言模型（L-LM）损失函数，分离判断与解释的损失计算，优先优化判断部分。此外，为提升模型对全局视觉特征的感知，我们构建了全局感知连接器（GAC），将多级视觉表示与语言模型对齐。在包含12个公共数据集的标准及新设计的One to Eleven跨域基准测试中，实验结果表明，我们的方法显著超越了现有最先进技术。

> Face Anti-Spoofing (FAS) is essential for ensuring the security and reliability of facial recognition systems. Most existing FAS methods are formulated as binary classification tasks, providing confidence scores without interpretation. They exhibit limited generalization in out-of-domain scenarios, such as new environments or unseen spoofing types. In this work, we introduce a multimodal large language model (MLLM) framework for FAS, termed Interpretable Face Anti-Spoofing (I-FAS), which transforms the FAS task into an interpretable visual question answering (VQA) paradigm. Specifically, we propose a Spoof-aware Captioning and Filtering (SCF) strategy to generate high-quality captions for FAS images, enriching the model's supervision with natural language interpretations. To mitigate the impact of noisy captions during training, we develop a Lopsided Language Model (L-LM) loss function that separates loss calculations for judgment and interpretation, prioritizing the optimization of the former. Furthermore, to enhance the model's perception of global visual features, we design a Globally Aware Connector (GAC) to align multi-level visual representations with the language model. Extensive experiments on standard and newly devised One to Eleven cross-domain benchmarks, comprising 12 public datasets, demonstrate that our method significantly outperforms state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2501.01720)