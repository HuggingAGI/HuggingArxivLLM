# 利用意图感知提示检测会话中的心理操纵

发布时间：2024年12月11日

`LLM应用` `心理健康`

> Detecting Conversational Mental Manipulation with Intent-Aware Prompting

# 摘要

> 心理操纵暗中且负面地扭曲决策，严重危害心理健康。尽管自然语言处理领域对心理健康护理的关注度不断提升，但由于在对话中检测细微、隐蔽策略颇为复杂，应对操纵问题的进展仍有限。在本文中，我们提出了意图感知提示（IAP）这一新颖方法，借助大型语言模型（LLM）来检测心理操纵，通过捕捉参与者的潜在意图，更深入地理解操纵策略。在 MentalManip 数据集上的实验结果显示，IAP 比其他先进的提示策略效果更优。特别值得一提的是，我们的方法大幅减少了假阴性，能在对阳性病例误判最少的情况下，检测出更多的心理操纵实例。本文的代码可在 https://github.com/Anton-Jiayuan-MA/Manip-IAP 获取。

> Mental manipulation severely undermines mental wellness by covertly and negatively distorting decision-making. While there is an increasing interest in mental health care within the natural language processing community, progress in tackling manipulation remains limited due to the complexity of detecting subtle, covert tactics in conversations. In this paper, we propose Intent-Aware Prompting (IAP), a novel approach for detecting mental manipulations using large language models (LLMs), providing a deeper understanding of manipulative tactics by capturing the underlying intents of participants. Experimental results on the MentalManip dataset demonstrate superior effectiveness of IAP against other advanced prompting strategies. Notably, our approach substantially reduces false negatives, helping detect more instances of mental manipulation with minimal misjudgment of positive cases. The code of this paper is available at https://github.com/Anton-Jiayuan-MA/Manip-IAP.

[Arxiv](https://arxiv.org/abs/2412.08414)