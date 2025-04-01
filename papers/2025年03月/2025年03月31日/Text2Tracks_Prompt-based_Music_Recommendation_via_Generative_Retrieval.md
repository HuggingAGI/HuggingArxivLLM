# Text2Tracks：基于提示的音乐推荐通过生成式检索实现

发布时间：2025年03月31日

`LLM应用` `音乐推荐`

> Text2Tracks: Prompt-based Music Recommendation via Generative Retrieval

# 摘要

> 近年来，大型语言模型（LLMs）让用户可以通过自然语言提示（如“你能推荐一些适合慢舞的老歌吗？”）提出高度个性化的音乐推荐请求。然而，传统的自回归生成方法存在三大局限：首先，其分词方式针对单词而非歌曲标题进行了优化；其次，需要额外的实体解析层来匹配歌曲标题与实际标识符；第三，解码步骤与标题长度成正比，影响推理速度。为解决这些问题，我们提出将基于提示的音乐推荐视为生成式检索任务，并引入Text2Tracks模型，通过直接从用户提示映射到相关歌曲ID实现高效推荐。实验表明，语义ID策略是Text2Tracks成功的关键，其表现远超传统方法。在正确选择轨道标识符的情况下，Text2Tracks在从语言提示检索轨道方面优于稀疏和密集检索解决方案。

> In recent years, Large Language Models (LLMs) have enabled users to provide highly specific music recommendation requests using natural language prompts (e.g. "Can you recommend some old classics for slow dancing?"). In this setup, the recommended tracks are predicted by the LLM in an autoregressive way, i.e. the LLM generates the track titles one token at a time. While intuitive, this approach has several limitation. First, it is based on a general purpose tokenization that is optimized for words rather than for track titles. Second, it necessitates an additional entity resolution layer that matches the track title to the actual track identifier. Third, the number of decoding steps scales linearly with the length of the track title, slowing down inference. In this paper, we propose to address the task of prompt-based music recommendation as a generative retrieval task. Within this setting, we introduce novel, effective, and efficient representations of track identifiers that significantly outperform commonly used strategies. We introduce Text2Tracks, a generative retrieval model that learns a mapping from a user's music recommendation prompt to the relevant track IDs directly. Through an offline evaluation on a dataset of playlists with language inputs, we find that (1) the strategy to create IDs for music tracks is the most important factor for the effectiveness of Text2Tracks and semantic IDs significantly outperform commonly used strategies that rely on song titles as identifiers (2) provided with the right choice of track identifiers, Text2Tracks outperforms sparse and dense retrieval solutions trained to retrieve tracks from language prompts.

[Arxiv](https://arxiv.org/abs/2503.24193)