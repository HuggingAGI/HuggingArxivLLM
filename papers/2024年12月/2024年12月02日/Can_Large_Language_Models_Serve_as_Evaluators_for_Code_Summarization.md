# 大型语言模型能否充当代码摘要的评估者呢？

发布时间：2024年12月02日

`LLM应用` `软件开发` `代码评估`

> Can Large Language Models Serve as Evaluators for Code Summarization?

# 摘要

> 代码总结将代码片段转化为自然语言描述，有助于程序理解和软件维护。多年来，针对这一任务已开发出众多方法，然而关键挑战依旧存在：如何有效评估生成的摘要质量。人工评估虽能有效衡量代码摘要质量，却费力且难以大规模开展。常用的自动指标，如 BLEU、ROUGE-L、METEOR 和 BERTScore 等，往往与人类判断存在偏差。本文探索了大型语言模型（LLMs）在评估代码总结方面的潜力。我们提出了 CODERPE（代码总结评估的角色扮演者）这一新方法，它借助角色扮演者提示来评估生成的摘要质量。具体而言，我们让一个 LLM 代理扮演不同角色，如代码审查员、代码作者、代码编辑和系统分析师。每个角色从连贯性、一致性、流畅性和相关性等关键维度评估代码摘要的质量。我们还通过运用各种提示策略，如思维链推理、上下文学习和定制评级表设计，进一步探究了 LLMs 作为评估者的稳健性。结果显示，LLMs 可作为代码总结方法的有效评估者。值得注意的是，我们基于 LLM 的评估器 CODERPE 与人类评估的 Spearman 相关性达 81.59%，比现有的 BERTScore 指标高 17.27%。

> Code summarization facilitates program comprehension and software maintenance by converting code snippets into natural-language descriptions. Over the years, numerous methods have been developed for this task, but a key challenge remains: effectively evaluating the quality of generated summaries. While human evaluation is effective for assessing code summary quality, it is labor-intensive and difficult to scale. Commonly used automatic metrics, such as BLEU, ROUGE-L, METEOR, and BERTScore, often fail to align closely with human judgments. In this paper, we explore the potential of Large Language Models (LLMs) for evaluating code summarization. We propose CODERPE (Role-Player for Code Summarization Evaluation), a novel method that leverages role-player prompting to assess the quality of generated summaries. Specifically, we prompt an LLM agent to play diverse roles, such as code reviewer, code author, code editor, and system analyst. Each role evaluates the quality of code summaries across key dimensions, including coherence, consistency, fluency, and relevance. We further explore the robustness of LLMs as evaluators by employing various prompting strategies, including chain-of-thought reasoning, in-context learning, and tailored rating form designs. The results demonstrate that LLMs serve as effective evaluators for code summarization methods. Notably, our LLM-based evaluator, CODERPE , achieves an 81.59% Spearman correlation with human evaluations, outperforming the existing BERTScore metric by 17.27%.

[Arxiv](https://arxiv.org/abs/2412.01333)