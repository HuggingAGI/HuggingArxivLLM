# OWL：通过世界文学探查跨语言记忆文本的召回能力

发布时间：2025年05月28日

`LLM应用` `跨语言技术`

> OWL: Probing Cross-Lingual Recall of Memorized Texts via World Literature

# 摘要

> **大型语言模型的记忆与跨语言迁移能力研究**

大型语言模型（LLMs）不仅能够记忆和回溯其预训练数据中的英文文本，还具备一定程度的跨语言记忆能力。然而，这种能力在多语言场景下的表现以及跨语言迁移的效果仍有待深入探索。本文通过实证研究，揭示了LLMs在多语言记忆与跨语言迁移方面的潜力。

**研究方法与数据集**  
我们构建了包含20本书籍的多语言对齐数据集OWL，共计31.5万个段落，覆盖十种语言：包括英语原文、官方翻译（越南语、西班牙语、土耳其语）以及六种低资源语言的新翻译（塞索托语、约鲁巴语、迈蒂利语、马达加斯加语、塞茨瓦纳语、塔希提语）。通过以下三个任务评估不同模型家族和规模的记忆能力：  
1. **直接探测**：要求模型识别书籍的标题和作者；  
2. **名字填空**：要求预测被遮蔽的角色名称；  
3. **前缀探测**：生成续写内容。  

**实验结果与发现**  
研究发现，LLMs能够跨语言回溯内容，即使在预训练数据中没有直接翻译的情况下。例如，GPT-4o在新翻译的段落中能够识别出69%的作者和书名，以及6%的被遮蔽实体。干扰操作（例如遮蔽字符、打乱单词顺序）会适度降低直接探测的准确性（官方翻译被打乱后准确率下降7%）。  

**研究意义**  
我们的研究结果不仅突显了跨语言记忆的能力，还为不同模型之间的差异提供了深入的见解，为未来多语言模型的开发与优化提供了有价值的参考。

> Large language models (LLMs) are known to memorize and recall English text from their pretraining data. However, the extent to which this ability generalizes to non-English languages or transfers across languages remains unclear. This paper investigates multilingual and cross-lingual memorization in LLMs, probing if memorized content in one language (e.g., English) can be recalled when presented in translation. To do so, we introduce OWL, a dataset of 31.5K aligned excerpts from 20 books in ten languages, including English originals, official translations (Vietnamese, Spanish, Turkish), and new translations in six low-resource languages (Sesotho, Yoruba, Maithili, Malagasy, Setswana, Tahitian). We evaluate memorization across model families and sizes through three tasks: (1) direct probing, which asks the model to identify a book's title and author; (2) name cloze, which requires predicting masked character names; and (3) prefix probing, which involves generating continuations. We find that LLMs consistently recall content across languages, even for texts without direct translation in pretraining data. GPT-4o, for example, identifies authors and titles 69% of the time and masked entities 6% of the time in newly translated excerpts. Perturbations (e.g., masking characters, shuffling words) modestly reduce direct probing accuracy (7% drop for shuffled official translations). Our results highlight the extent of cross-lingual memorization and provide insights on the differences between the models.

[Arxiv](https://arxiv.org/abs/2505.22945)