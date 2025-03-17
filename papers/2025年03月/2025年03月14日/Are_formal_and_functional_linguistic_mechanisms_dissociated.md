# 形式与功能语言机制是否分离？

发布时间：2025年03月14日

`LLM理论` `神经科学`

> Are formal and functional linguistic mechanisms dissociated?

# 摘要

> 尽管大型语言模型（LLMs）的能力日益增强，但这些能力的分布并不均衡：它们在形式语言任务方面表现出色，例如生成流畅且语法正确的文本，但在推理和一致的事实检索等功能性语言任务上则显得较为吃力。受到神经科学的启发，近期研究表明，为了在形式和功能性语言任务上双双取得成功，LLMs应为每个任务采用不同的机制；这种专门化机制可以是预设的，也可以通过训练自发形成。本文探讨：当前模型，随着功能性语言能力的迅速提升，是否表现出形式与功能性语言机制的明显分化？我们通过发现并比较负责各类形式与功能性任务的"电路"或最小计算子图来回答这一问题。在对5种LLMs进行的10项不同任务的对比中，我们发现，尽管形式与功能性任务的电路确实存在很少重叠，但形式语言任务之间的重叠同样很少，这与人类大脑中的情况相似。因此，一个统一且与功能性任务电路不同的单一形式语言网络依然难以捉摸。然而，在跨任务忠实性方面——即一种电路解决另一种任务的能力——我们观察到形式与功能性机制之间的分离，这表明形式任务之间可能存在共享机制。


> Although large language models (LLMs) are increasingly capable, these capabilities are unevenly distributed: they excel at formal linguistic tasks, such as producing fluent, grammatical text, but struggle more with functional linguistic tasks like reasoning and consistent fact retrieval. Inspired by neuroscience, recent work suggests that to succeed on both formal and functional linguistic tasks, LLMs should use different mechanisms for each; such localization could either be built-in or emerge spontaneously through training. In this paper, we ask: do current models, with fast-improving functional linguistic abilities, exhibit distinct localization of formal and functional linguistic mechanisms? We answer this by finding and comparing the "circuits", or minimal computational subgraphs, responsible for various formal and functional tasks. Comparing 5 LLMs across 10 distinct tasks, we find that while there is indeed little overlap between circuits for formal and functional tasks, there is also little overlap between formal linguistic tasks, as exists in the human brain. Thus, a single formal linguistic network, unified and distinct from functional task circuits, remains elusive. However, in terms of cross-task faithfulness - the ability of one circuit to solve another's task - we observe a separation between formal and functional mechanisms, suggesting that shared mechanisms between formal tasks may exist.

[Arxiv](https://arxiv.org/abs/2503.11302)