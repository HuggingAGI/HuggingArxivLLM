# 以少优化对齐：借助数据增强实现个性化评估

发布时间：2024年12月10日

`LLM应用` `语言模型`

> Optimizing Alignment with Less: Leveraging Data Augmentation for Personalized Evaluation

# 摘要

> 大型语言模型（LLMs）的自动评估在当下是个热门话题。然而，判断和评估任务通常具有主观性，且受多种因素影响，导致适应难度较大。尽管众多研究表明，最先进的专有 LLMs 与人类评估者相比具备一定能力，但它们往往难以长期适应参考评估者，而这是实现个性化判断的必要条件。另外，许多工作尝试将开放的 LLMs 用作评判者或评估者，可这些努力常常忽略了处理稀缺数据时的局限性。个性化判断天然与有限的数据场景相关联，这在众多现实问题中屡见不鲜。我们的工作旨在提出一种数据增强技术，从有限的数据中选取更有效的样本，让开放的 LLM 契合人类偏好。我们的工作在与参考评判者的皮尔逊相关性方面，相较于基线提升了约 7%，在数学推理评估任务中，相较于基础模型（Llama3.1-8B-Instruct）提升了 30%。这表明，通过增强并选取更有效的偏好数据，我们的方法能够超越基线方法。

> Automatic evaluation by large language models (LLMs) is a prominent topic today; however, judgment and evaluation tasks are often subjective and influenced by various factors, making adaptation challenging. While many studies demonstrate the capabilities of state-of-the-art proprietary LLMs in comparison to human evaluators, they often struggle to adapt to reference evaluators over time, a requirement for achieving personalized judgment. Additionally, numerous works have attempted to apply open LLMs as judges or evaluators, but these efforts frequently overlook the limitations of working with scarce data. Personalized judgment is inherently associated with limited data scenarios, which are common in many real-world problems. Our work aims to present a data augmentation technique to select a more effective sample from limited data in order to align an open LLM with human preference. Our work achieves approximately 7% improvements in Pearson correlation with a reference judge over the baseline,and 30% improvement over the base model (Llama3.1-8B-Instruct) in the mathematical reasoning evaluation task. demonstrating that augmenting selecting more effective preference data enables our approach to surpass baseline methods.

[Arxiv](https://arxiv.org/abs/2412.07429)