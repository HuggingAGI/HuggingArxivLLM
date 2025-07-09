# 为何我们会有这些感受：电商领域中情感及其引发情感的意见点的同步识别

发布时间：2025年07月07日

`LLM应用

论文摘要：电商平台上的客户评论蕴含着影响购买决策的关键情感信号。然而，现有研究尚未探索电商评论中情绪检测与解释性文本片段识别的联合任务——这一空白限制了我们对客户情感反应触发机制的理解。为填补这一空白，我们提出了一种新型联合任务EOT（情绪检测与观点触发点提取），该任务基于Plutchik的8种基本情绪理论，显式建模了因果文本片段（观点触发点）与情感维度（情绪类别）之间的关系。在缺乏标注数据的情况下，我们创建了EOT-X，一个包含2,400条人工标注评论的数据集，涵盖了细致的情绪分类与观点触发点。我们评估了23种大型语言模型（LLMs），并提出了EOT-DETECT，一个包含系统推理与自我反思的结构化提示框架。我们的框架在跨电商平台领域中超越了零样本与链式思维技术。

LLM应用` `情感分析`

> Why We Feel What We Feel: Joint Detection of Emotions and Their Opinion Triggers in E-commerce

# 摘要

> 电商平台上的客户评论蕴含着影响购买决策的关键情感信号。然而，现有研究尚未探索电商评论中情绪检测与解释性文本片段识别的联合任务——这一空白限制了我们对客户情感反应触发机制的理解。为填补这一空白，我们提出了一种新型联合任务EOT（情绪检测与观点触发点提取），该任务基于Plutchik的8种基本情绪理论，显式建模了因果文本片段（观点触发点）与情感维度（情绪类别）之间的关系。在缺乏标注数据的情况下，我们创建了EOT-X，一个包含2,400条人工标注评论的数据集，涵盖了细致的情绪分类与观点触发点。我们评估了23种大型语言模型（LLMs），并提出了EOT-DETECT，一个包含系统推理与自我反思的结构化提示框架。我们的框架在跨电商平台领域中超越了零样本与链式思维技术。


> Customer reviews on e-commerce platforms capture critical affective signals that drive purchasing decisions. However, no existing research has explored the joint task of emotion detection and explanatory span identification in e-commerce reviews - a crucial gap in understanding what triggers customer emotional responses. To bridge this gap, we propose a novel joint task unifying Emotion detection and Opinion Trigger extraction (EOT), which explicitly models the relationship between causal text spans (opinion triggers) and affective dimensions (emotion categories) grounded in Plutchik's theory of 8 primary emotions. In the absence of labeled data, we introduce EOT-X, a human-annotated collection of 2,400 reviews with fine-grained emotions and opinion triggers. We evaluate 23 Large Language Models (LLMs) and present EOT-DETECT, a structured prompting framework with systematic reasoning and self-reflection. Our framework surpasses zero-shot and chain-of-thought techniques, across e-commerce domains.

[Arxiv](https://arxiv.org/abs/2507.04708)