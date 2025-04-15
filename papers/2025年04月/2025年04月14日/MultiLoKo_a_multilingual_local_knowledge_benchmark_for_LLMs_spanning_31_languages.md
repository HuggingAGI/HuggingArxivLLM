# MultiLoKo：覆盖31种语言的大型语言模型的多语言本地知识基准

发布时间：2025年04月14日

`LLM应用` `多语言模型` `跨语言`

> MultiLoKo: a multilingual local knowledge benchmark for LLMs spanning 31 languages

# 摘要

> 我们推出了MultiLoKo，一个全新的基准测试，用于评估大型语言模型（LLMs）的多语言能力，涵盖31种语言。MultiLoKo由三部分组成：每种语言包含500个本地相关问题的主部分，以及两种翻译部分，分别包含从30种非英语语言到英语和反之的人工翻译。为了便于比较，我们还发布了相应的机器生成翻译。数据均匀分配到两个分割集中：一个开发集和一个盲测、分布外的测试集。MultiLoKo可用于研究LLMs的多语言能力以及多语言基准创建的元问题。我们评估了11个标榜为多语言的基础模型和聊天模型在MultiLoKo上的表现，分析了它们的平均性能、跨语言一致性、回答能力对问题语言的依赖性，以及哪些语言最难。研究发现所有模型在MultiLoKo上的表现均不尽如人意，表现为低平均分和最佳与最差语言之间的显著差异。此外，问题语言对模型表现的影响显著，表明跨语言知识迁移效果欠佳。值得注意的是，使用本地数据与英语翻译数据相比，最佳模型的得分差异超过20分，大幅改变了某些语言的难度评估。至于机器翻译与人工翻译的对比，机器翻译对语言难度排序的影响较弱，模型排名差异更大，且所有模型的估计表现均有显著下降。

> We present MultiLoKo, a new benchmark for evaluating multilinguality in LLMs covering 31 languages. MultiLoKo consists of three partitions: a main partition consisting of 500 questions per language, separately sourced to be locally relevant to the specific language, and two translated partitions, containing human-authored translations from 30 non-English languages to English and vice versa. For comparison, we also release corresponding machine-authored translations. The data is equally distributed over two splits: a dev split and a blind, out-of-distribution test split. MultiLoKo can be used to study a variety of questions regarding the multilinguality of LLMs as well as meta-questions about multilingual benchmark creation. We compute MultiLoKo scores for 11 base and chat models marketed to be multilingual and study their average performance, their performance parity across languages, how much their ability to answer questions depends on the question language, and which languages are most difficult. None of the models we studied performs well on MultiLoKo, as indicated by low average scores as well as large differences between the best and worst scoring languages. Furthermore, we find a substantial effect of the question language, indicating sub-optimal knowledge transfer between languages. Lastly, we find that using local vs English-translated data can result in differences more than 20 points for the best performing models, drastically change the estimated difficulty of some languages. For using machines instead of human translations, we find a weaker effect on ordering of language difficulty, a larger difference in model rankings, and a substantial drop in estimated performance for all models.

[Arxiv](https://arxiv.org/abs/2504.10356)