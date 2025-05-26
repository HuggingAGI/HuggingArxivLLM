# VoxRAG: 语音问答迈向无需转录的RAG系统的重要一步

发布时间：2025年05月22日

`RAG` `语音处理` `语音检索`

> VoxRAG: A Step Toward Transcription-Free RAG Systems in Spoken Question Answering

# 摘要

> VoxRAG是一款模块化的语音到语音检索增强生成系统，它无需转录，直接从语音查询中检索语义相关的音频片段。该系统采用静音感知分段、说话人分离、CLAP音频嵌入和基于L2归一化余弦相似度的FAISS检索技术。我们构建了一个包含50个查询的测试集，由英语母语者以语音形式录制。通过LLM作为评估者对检索质量进行标注。对于高度相关的片段，余弦相似度在10个检索结果中的召回率达到了0.34。对于有一定相关性的片段，召回率提升至0.60，nDCG@10达到0.27，表明主题对齐效果显著。答案质量在相关性、准确性、完整性和精确性四个维度上进行了评估，评分范围为0-2分，平均得分分别为0.84、0.58、0.56和0.46。尽管精确性和检索质量仍为关键限制，但VoxRAG证明了在RAG系统中实现无转录的语音到语音检索是可行的。

> We introduce VoxRAG, a modular speech-to-speech retrieval-augmented generation system that bypasses transcription to retrieve semantically relevant audio segments directly from spoken queries. VoxRAG employs silence-aware segmentation, speaker diarization, CLAP audio embeddings, and FAISS retrieval using L2-normalized cosine similarity. We construct a 50-query test set recorded as spoken input by a native English speaker. Retrieval quality was evaluated using LLM-as-a-judge annotations. For very relevant segments, cosine similarity achieved a Recall@10 of 0.34. For somewhat relevant segments, Recall@10 rose to 0.60 and nDCG@10 to 0.27, highlighting strong topical alignment. Answer quality was judged on a 0--2 scale across relevance, accuracy, completeness, and precision, with mean scores of 0.84, 0.58, 0.56, and 0.46 respectively. While precision and retrieval quality remain key limitations, VoxRAG shows that transcription-free speech-to-speech retrieval is feasible in RAG systems.

[Arxiv](https://arxiv.org/abs/2505.17326)