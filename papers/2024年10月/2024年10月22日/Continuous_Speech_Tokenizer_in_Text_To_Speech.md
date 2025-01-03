# # 文本转语音中的连续语音分词器

发布时间：2024年10月22日

`LLM应用` `语音处理`

> Continuous Speech Tokenizer in Text To Speech

# 摘要

> 在大型语言模型时代，语音与语言的融合备受瞩目。离散语音标记常用于文本转语音任务，便于语音压缩和联合训练，但存在信息丢失问题。为此，我们提出了一种简单高效的连续语音标记器及基于此的文本转语音模型。实验表明，基于连续语音标记器的语音语言模型连续性更佳，估计平均意见分数（MoS）更高，这得益于其在频域中低频和高频的更好信息保留能力。

> The fusion of speech and language in the era of large language models has garnered significant attention. Discrete speech token is often utilized in text-to-speech tasks for speech compression and portability, which is convenient for joint training with text and have good compression efficiency. However, we found that the discrete speech tokenizer still suffers from information loss. Therefore, we propose a simple yet effective continuous speech tokenizer and a text-to-speech model based on continuous speech tokens. Our results show that the speech language model based on the continuous speech tokenizer has better continuity and higher estimated Mean Opinion Scores (MoS). This enhancement is attributed to better information preservation rate of the continuous speech tokenizer across both low and high frequencies in the frequency domain.

[Arxiv](https://arxiv.org/abs/2410.17081)