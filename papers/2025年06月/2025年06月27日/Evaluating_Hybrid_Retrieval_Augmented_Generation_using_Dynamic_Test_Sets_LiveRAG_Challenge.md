# # 探索混合检索增强生成：基于动态测试集的 LiveRAG 挑战

发布时间：2025年06月27日

`RAG` `问答系统`

> Evaluating Hybrid Retrieval Augmented Generation using Dynamic Test Sets: LiveRAG Challenge

# 摘要

> 我们参加了LiveRAG Challenge 2025，该挑战赛基于FineWeb-10BT语料库，通过动态测试集评估检索增强生成（RAG）系统。我们的最终方案结合了稀疏（BM25）和密集（E5）检索方法，并通过Falcon3-10B-Instruct生成相关且忠实的回答。通过对200个使用DataMorgana生成的合成问题（涵盖64种独特问答组合）进行系统性评估，我们发现神经重排序方法RankLLaMA将MAP从0.523提升至0.797（52%的相对提升），但计算成本显著增加（每个问题84秒 vs 1.74秒）。尽管DSPy优化的提示策略在语义相似度上更优（0.771 vs 0.668），但其0%的拒绝率引发了关于过度自信和泛化能力的担忧。在25支参赛队伍中，我们提交的无重排序混合系统在忠实性方面排名第四，在正确性方面排名第十一位。跨问题类别的分析表明，问题与文档之间的词汇对齐是我们在开发集上性能的最强预测指标，文档相似的措辞将余弦相似度从0.562提升至0.762。

> We present our submission to the LiveRAG Challenge 2025, which evaluates retrieval-augmented generation (RAG) systems on dynamic test sets using the FineWeb-10BT corpus. Our final hybrid approach combines sparse (BM25) and dense (E5) retrieval methods and then aims to generate relevant and faithful answers with Falcon3-10B-Instruct. Through systematic evaluation on 200 synthetic questions generated with DataMorgana across 64 unique question-user combinations, we demonstrate that neural re-ranking with RankLLaMA improves MAP from 0.523 to 0.797 (52% relative improvement) but introduces prohibitive computational costs (84s vs 1.74s per question). While DSPy-optimized prompting strategies achieved higher semantic similarity (0.771 vs 0.668), their 0% refusal rates raised concerns about over-confidence and generalizability. Our submitted hybrid system without re-ranking achieved 4th place in faithfulness and 11th place in correctness among 25 teams. Analysis across question categories reveals that vocabulary alignment between questions and documents was the strongest predictor of performance on our development set, with document-similar phrasing improving cosine similarity from 0.562 to 0.762.

[Arxiv](https://arxiv.org/abs/2506.22644)