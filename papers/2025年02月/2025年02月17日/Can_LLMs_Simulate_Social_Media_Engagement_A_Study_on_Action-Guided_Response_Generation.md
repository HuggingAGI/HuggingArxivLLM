# 大型语言模型能否模拟社交媒体互动？——一项关于行动引导响应生成的研究

发布时间：2025年02月17日

`LLM应用` `社交媒体`

> Can LLMs Simulate Social Media Engagement? A Study on Action-Guided Response Generation

# 摘要

> 社交媒体让用户体验热门话题的动态互动，近期研究挖掘了大型语言模型（LLMs）在生成回复上的潜力。尽管有些研究将LLMs用于模拟社交媒体用户行为，但它们更关注实际应用和扩展性，而非深入探讨LLMs与人类行为的契合度。本文通过行动引导的回复生成，分析LLMs模拟社交媒体互动的能力：模型先预测用户最可能的互动动作——转推、引用或重写——针对热门帖子，再根据预测的动作生成个性化回复。我们以X平台上讨论的重大社会事件为背景，对GPT-4o-mini、O1-mini和DeepSeek-R1进行了基准测试。研究发现，零样本LLMs在动作预测上不如BERT，而少样本提示最初降低了LLMs的预测准确性。然而，在回复生成方面，少样本LLMs与真实帖子的语义对齐更强。

> Social media enables dynamic user engagement with trending topics, and recent research has explored the potential of large language models (LLMs) for response generation. While some studies investigate LLMs as agents for simulating user behavior on social media, their focus remains on practical viability and scalability rather than a deeper understanding of how well LLM aligns with human behavior. This paper analyzes LLMs' ability to simulate social media engagement through action guided response generation, where a model first predicts a user's most likely engagement action-retweet, quote, or rewrite-towards a trending post before generating a personalized response conditioned on the predicted action. We benchmark GPT-4o-mini, O1-mini, and DeepSeek-R1 in social media engagement simulation regarding a major societal event discussed on X. Our findings reveal that zero-shot LLMs underperform BERT in action prediction, while few-shot prompting initially degrades the prediction accuracy of LLMs with limited examples. However, in response generation, few-shot LLMs achieve stronger semantic alignment with ground truth posts.

[Arxiv](https://arxiv.org/abs/2502.12073)