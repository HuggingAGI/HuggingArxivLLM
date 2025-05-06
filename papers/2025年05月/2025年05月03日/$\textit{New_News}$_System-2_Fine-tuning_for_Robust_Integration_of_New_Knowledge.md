# $	extit{New News}$: 系统-2微调：稳健整合新知的方法

发布时间：2025年05月03日

`LLM理论` `跨领域应用`

> $\textit{New News}$: System-2 Fine-tuning for Robust Integration of New Knowledge

# 摘要

> 人类和智能动物能够轻松吸收新信息（“新闻”）并准确提取其对下游任务的启示。虽然大型语言模型（LLMs）可以通过上下文学习（ICL）在明确给出新闻作为上下文时实现这一点，但模型通过微调将学习成果固化到权重中仍然具有挑战性。本文介绍了一个名为《新新闻》的数据集，其中包含跨多个领域（数学、编程、发现、排行榜、事件）的假设但合理的新闻，并附带下游评估问题，这些问题的正确答案严重依赖于对新闻的理解和吸收。我们首先揭示了一个显著的差距：在我们的新闻数据集上，简单的微调与上下文学习（FT-ICL差距）之间存在巨大差异。为了解决这一差距，我们探索了一套自我对弈数据生成协议——包括改写、启示和自洽问答（Self-QAs）——旨在将模型在上下文中的知识提炼到模型权重中（无上下文），我们称之为《系统-2微调》（Sys2-FT）。我们使用Qwen 2.5系列模型，系统地评估了ICL和Sys2-FT在数据领域和模型规模上的性能。我们的结果显示，《系统-2微调》中的自洽问答协议显著提升了模型对新闻的权重学习效果。此外，我们发现了一种《上下文遮蔽效应》，即先在上下文中训练新闻，再使用其改写或问答进行训练，反而会降低对新闻的学习效果。最后，我们展示了《系统-2微调》中初步出现的扩展规律。


> Humans and intelligent animals can effortlessly internalize new information ("news") and accurately extract the implications for performing downstream tasks. While large language models (LLMs) can achieve this through in-context learning (ICL) when the news is explicitly given as context, fine-tuning remains challenging for the models to consolidate learning in weights. In this paper, we introduce $\textit{New News}$, a dataset composed of hypothetical yet plausible news spanning multiple domains (mathematics, coding, discoveries, leaderboards, events), accompanied by downstream evaluation questions whose correct answers critically depend on understanding and internalizing the news. We first demonstrate a substantial gap between naive fine-tuning and in-context learning (FT-ICL gap) on our news dataset. To address this gap, we explore a suite of self-play data generation protocols -- paraphrases, implications and Self-QAs -- designed to distill the knowledge from the model with context into the weights of the model without the context, which we term $\textit{System-2 Fine-tuning}$ (Sys2-FT). We systematically evaluate ICL and Sys2-FT performance across data domains and model scales with the Qwen 2.5 family of models. Our results demonstrate that the self-QA protocol of Sys2-FT significantly improves models' in-weight learning of the news. Furthermore, we discover the $\textit{contexual shadowing effect}$, where training with the news $\textit{in context}$ followed by its rephrases or QAs degrade learning of the news. Finally, we show preliminary evidence of an emerging scaling law of Sys2-FT.

[Arxiv](https://arxiv.org/abs/2505.01812)