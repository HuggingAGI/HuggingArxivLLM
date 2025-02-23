# TALKPLAY：利用大型语言模型实现多模态音乐推荐

发布时间：2025年02月19日

`LLM应用` `音乐推荐`

> TALKPLAY: Multimodal Music Recommendation with Large Language Models

# 摘要

> 我们推出 TalkPlay，一款将推荐任务转化为大型语言模型 token 生成的多模态音乐推荐系统。TalkPlay 通过扩展的 token 词汇表，整合了音频、歌词、元数据、语义标签及播放列表共现等多种模态信息来表示音乐。基于这些丰富表示，模型通过预测音乐推荐对话中的下一个 token 学习生成推荐，这一过程需要捕捉自然语言查询与响应以及音乐项目间的关联。简言之，TalkPlay 将音乐推荐转化为自然语言理解任务，模型预测对话 token 的能力直接优化了查询与项目的匹配度。我们的方法摈弃了传统推荐-对话管道的复杂性，实现了端到端的查询感知音乐推荐学习。实验中，TalkPlay 成功训练，并在多方面超越基线方法，充分展现了其作为对话式音乐推荐器的卓越上下文理解能力。

> We present TalkPlay, a multimodal music recommendation system that reformulates the recommendation task as large language model token generation. TalkPlay represents music through an expanded token vocabulary that encodes multiple modalities - audio, lyrics, metadata, semantic tags, and playlist co-occurrence. Using these rich representations, the model learns to generate recommendations through next-token prediction on music recommendation conversations, that requires learning the associations natural language query and response, as well as music items. In other words, the formulation transforms music recommendation into a natural language understanding task, where the model's ability to predict conversation tokens directly optimizes query-item relevance. Our approach eliminates traditional recommendation-dialogue pipeline complexity, enabling end-to-end learning of query-aware music recommendations. In the experiment, TalkPlay is successfully trained and outperforms baseline methods in various aspects, demonstrating strong context understanding as a conversational music recommender.

[Arxiv](https://arxiv.org/abs/2502.13713)