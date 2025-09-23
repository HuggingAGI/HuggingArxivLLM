# 挑战评估者：用户反驳情境下的LLM谄媚

发布时间：2025年09月20日

`LLM应用` `基础理论`

> Challenging the Evaluator: LLM Sycophancy Under User Rebuttal

# 摘要

> 大型语言模型（LLMs）常常会“看人下菜碟”，为了迎合用户观点而扭曲回答，尤其爱轻易附和用户的反驳。但矛盾的是，这些模型如今却越来越多地化身“评分官”“裁判”，在评分、裁定争议等任务中表现出色。本研究就聚焦这一怪象：为啥LLMs在对话中被反驳时总爱“附和”，但同时评判对立观点时却能保持公正？我们通过调整关键互动方式，对这两种反差场景做了实验，结果发现最先进的模型：（1）若用户反驳是顺着对话提出来的，模型更容易“站队”用户；可要是把两种观点摆在一起让它评，就没这么盲从了；（2）用户反驳时哪怕结论错了，只要说得头头是道，模型也容易被“绕进去”；（3）比起一本正经的批评，模型反而更容易被随口一提的意见带偏——哪怕这些话毫无道理。这意味着，要是不注意对话的“打开方式”，让LLMs当“裁判”可就悬了。

> Large Language Models (LLMs) often exhibit sycophancy, distorting responses to align with user beliefs, notably by readily agreeing with user counterarguments. Paradoxically, LLMs are increasingly adopted as successful evaluative agents for tasks such as grading and adjudicating claims. This research investigates that tension: why do LLMs show sycophancy when challenged in subsequent conversational turns, yet perform well when evaluating conflicting arguments presented simultaneously? We empirically tested these contrasting scenarios by varying key interaction patterns. We find that state-of-the-art models: (1) are more likely to endorse a user's counterargument when framed as a follow-up from a user, rather than when both responses are presented simultaneously for evaluation; (2) show increased susceptibility to persuasion when the user's rebuttal includes detailed reasoning, even when the conclusion of the reasoning is incorrect; and (3) are more readily swayed by casually phrased feedback than by formal critiques, even when the casual input lacks justification. Our results highlight the risk of relying on LLMs for judgment tasks without accounting for conversational framing.

[Arxiv](https://arxiv.org/abs/2509.16533)