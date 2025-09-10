# 具备竞争力的音频-语言模型：基于公共数据的高效单阶段训练

发布时间：2025年09月09日

`LLM应用` `媒体与娱乐`

> Competitive Audio-Language Models with Data-Efficient Single-Stage Training on Public Data

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理（NLP）领域，但它们与音频的融合却仍显探索不足——尽管音频在人类交流中占据核心地位。我们推出了Falcon3-Audio，这是一系列基于指令微调大型语言模型和Whisper编码器构建的音频-语言模型（ALMs）。凭借极少的公开音频数据——不到30K小时（5K条独特音频）——Falcon3-Audio-7B在MMAU基准测试中达到了开源模型的最佳报告性能，得分64.14，与R1-AQA持平，同时凭借更出色的数据与参数效率、单阶段训练及透明度彰显优势。值得关注的是，我们最小的1B模型即便与参数规模在2B到13B之间的更大开源模型相比，依然具有竞争力。通过大量消融实验，我们发现常见的复杂设计——例如课程学习、多音频编码器及复杂的交叉注意力连接机制——并非实现高性能的必要条件，即便与训练数据超500K小时的模型相比亦是如此。

> Large language models (LLMs) have transformed NLP, yet their integration with audio remains underexplored -- despite audio's centrality to human communication. We introduce Falcon3-Audio, a family of Audio-Language Models (ALMs) built on instruction-tuned LLMs and Whisper encoders. Using a remarkably small amount of public audio data -- less than 30K hours (5K unique) -- Falcon3-Audio-7B matches the best reported performance among open-weight models on the MMAU benchmark, with a score of 64.14, matching R1-AQA, while distinguishing itself through superior data and parameter efficiency, single-stage training, and transparency. Notably, our smallest 1B model remains competitive with larger open models ranging from 2B to 13B parameters. Through extensive ablations, we find that common complexities -- such as curriculum learning, multiple audio encoders, and intricate cross-attention connectors -- are not required for strong performance, even compared to models trained on over 500K hours of data.

[Arxiv](https://arxiv.org/abs/2509.07526)