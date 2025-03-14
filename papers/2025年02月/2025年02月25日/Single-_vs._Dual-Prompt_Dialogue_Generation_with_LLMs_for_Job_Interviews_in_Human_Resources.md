# 单提示与双提示对比：利用大语言模型生成对话在人力资源职位面试中的应用

发布时间：2025年02月25日

`LLM应用` `人力资源` `对话生成`

> Single- vs. Dual-Prompt Dialogue Generation with LLMs for Job Interviews in Human Resources

# 摘要

> 在对话式AI代理中优化语言模型，需要大量示例对话。越来越多的对话是通过强大的大型语言模型（LLMs）合成生成的，尤其是在难以获取真实人类数据的领域。人力资源（HR）就是一个典型领域。在此背景下，我们比较了两种基于LLMs的对话生成方法，用于生成HR面试的场景，并评估哪种方法能生成更高质量、更难与真实人类对话区分的对话。第一种方法使用单个提示生成完整面试对话，而第二种方法则通过两个智能体相互对话生成。为了评估每种方法的对话质量，我们让一个裁判LLM通过成对比较面试来判断是否使用了AI生成。结果显示，尽管双提示方法的代币成本增加了六倍，但生成的面试胜率却比单提示方法高出十倍。这一差异在使用GPT-4o或Llama 3.3 70B进行面试生成或质量评估时保持一致。

> Optimizing language models for use in conversational agents requires large quantities of example dialogues. Increasingly, these dialogues are synthetically generated by using powerful large language models (LLMs), especially in domains with challenges to obtain authentic human data. One such domain is human resources (HR). In this context, we compare two LLM-based dialogue generation methods for the use case of generating HR job interviews, and assess whether one method generates higher-quality dialogues that are more challenging to distinguish from genuine human discourse. The first method uses a single prompt to generate the complete interview dialog. The second method uses two agents that converse with each other. To evaluate dialogue quality under each method, we ask a judge LLM to determine whether AI was used for interview generation, using pairwise interview comparisons. We demonstrate that despite a sixfold increase in token cost, interviews generated with the dual-prompt method achieve a win rate up to ten times higher than those generated with the single-prompt method. This difference remains consistent regardless of whether GPT-4o or Llama 3.3 70B is used for either interview generation or judging quality.

[Arxiv](https://arxiv.org/abs/2502.18650)