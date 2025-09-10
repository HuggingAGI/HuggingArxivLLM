# M-BRe：借助大型语言模型从无标签文本中发现关系抽取训练样本

发布时间：2025年09月09日

`LLM应用` `基础理论`

> M-BRe: Discovering Training Samples for Relation Extraction from Unlabeled Texts with Large Language Models

# 摘要

> 在关系抽取（RE）领域，手动标注训练数据的成本往往高得令人望而却步——毕竟文本中包含目标关系的句子不仅稀少，还极难定位。因此，研发一种能从无标签文本中自动提取训练实例以训练RE模型的高效方法极具价值。近年来，大型语言模型（LLMs）已广泛应用于各类自然语言处理任务，RE也从中受益匪浅。但在利用LLMs处理含预定义关系类别的RE时，却面临两大核心挑战：一是在多分类场景下，LLMs难以全面捕捉每个关系的语义，导致效果不尽如人意；二是若为每个关系单独进行二分类虽能缓解此问题，却会产生巨大计算开销，使实际应用的时间复杂度变得不可行。为此，本文提出名为M-BRe的框架，用于从无标签文本中提取RE训练实例。该框架通过关系分组、关系抽取和标签决策三个模块，融合了上述两种分类方法的优势。大量实验证实，该框架在从无标签文本中为RE挖掘高质量训练样本方面表现出优越性能。

> For Relation Extraction (RE), the manual annotation of training data may be prohibitively expensive, since the sentences that contain the target relations in texts can be very scarce and difficult to find. It is therefore beneficial to develop an efficient method that can automatically extract training instances from unlabeled texts for training RE models. Recently, large language models (LLMs) have been adopted in various natural language processing tasks, with RE also benefiting from their advances. However, when leveraging LLMs for RE with predefined relation categories, two key challenges arise. First, in a multi-class classification setting, LLMs often struggle to comprehensively capture the semantics of every relation, leading to suboptimal results. Second, although employing binary classification for each relation individually can mitigate this issue, it introduces significant computational overhead, resulting in impractical time complexity for real-world applications. Therefore, this paper proposes a framework called M-BRe to extract training instances from unlabeled texts for RE. It utilizes three modules to combine the advantages of both of the above classification approaches: Relation Grouping, Relation Extraction, and Label Decision. Extensive experiments confirm its superior capability in discovering high-quality training samples from unlabeled texts for RE.

[Arxiv](https://arxiv.org/abs/2509.07730)