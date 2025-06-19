# # MinosEval  
MinosEval：通过区分事实性与非事实性，为开放性问答量身定制评估方案，借助大型语言模型（LLMs）实现精准评估。

发布时间：2025年06月18日

`LLM应用

理由：这篇论文探讨了大型语言模型在开放性问答任务中的评估方法，提出了MinosEval，一种根据问题类型进行评估的新方法。它属于LLM的应用领域，因为它专注于如何有效评估和利用LLMs在特定任务中的性能。` `问答系统`

> MinosEval: Distinguishing Factoid and Non-Factoid for Tailored Open-Ended QA Evaluation with LLMs

# 摘要

> 开放性问答（QA）是评估大型语言模型（LLMs）能力的关键任务。相较于封闭式问答，它需要更长的回答、更细致的推理以及多样化的表达，因此精细且可解释的自动评估既重要又具挑战性。传统指标如ROUGE和BERTScore难以捕捉模型回答与参考答案的语义相似性。现有基于LLM的评估方法，如成对或成组比较候选答案，缺乏直观的可解释性。虽然逐点打分提供了一些描述，但无法适应不同问题内容。特别值得注意的是，现有方法忽视了事实型与非事实型问题的区别。为了解决这些挑战，我们提出了	extbf{MinosEval}，这是一种新颖的评估方法，首先区分开放性问题类型，然后根据不同评估策略对候选答案进行排序。对于事实型问题，它采用自适应关键点评分策略；而对于非事实型问题，则使用实例感知的成组排序策略。我们在多个开放性QA数据集上进行了实验，包括自行构建的包含更多候选回答的数据集，以补充社区资源。实验结果表明，MinosEval更符合人工标注，并提供更具可解释性的结果。

> Open-ended question answering (QA) is a key task for evaluating the capabilities of large language models (LLMs). Compared to closed-ended QA, it demands longer answer statements, more nuanced reasoning processes, and diverse expressions, making refined and interpretable automatic evaluation both crucial and challenging. Traditional metrics like ROUGE and BERTScore struggle to capture semantic similarities due to different patterns between model responses and reference answers. Current LLM-based evaluation approaches, such as pairwise or listwise comparisons of candidate answers, lack intuitive interpretability. While pointwise scoring of each response provides some descriptions, it fails to adapt across different question contents. Most notably, existing methods overlook the distinction between factoid and non-factoid questions. To address these challenges, we propose \textbf{MinosEval}, a novel evaluation method that first distinguishes open-ended questions and then ranks candidate answers using different evaluation strategies. For factoid questions, it applies an adaptive key-point scoring strategy, while for non-factoid questions, it uses an instance-aware listwise ranking strategy. Experiments on multiple open-ended QA datasets, including self-built ones with more candidate responses to complement community resources, show that MinosEval better aligns with human annotations and offers more interpretable results.

[Arxiv](https://arxiv.org/abs/2506.15215)