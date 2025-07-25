# # 近期远场对话语音识别趋势：对 CHiME-7 和 8 DASR 挑战的综述
远场对话语音识别领域近期呈现显著发展趋势，本文对 CHiME-7 和 CHiME-8 的 DASR 挑战进行了深入综述。

发布时间：2025年07月24日

`其他` `语音识别` `语音处理`

> Recent Trends in Distant Conversational Speech Recognition: A Review of CHiME-7 and 8 DASR Challenges

# 摘要

> CHiME-7 和 8 的远场语音识别 (DASR) 挑战聚焦于多通道、可泛化的联合语音识别 (ASR) 和对话语音的说话人分离技术。在 9 个团队提交的 32 个多样化系统中，这些挑战推动了该领域最前沿的研究进展。本文概述了这些挑战的设计、评估指标、数据集和基线系统，并分析了参赛提交的关键趋势。通过分析可以发现：

1) 大多数参赛团队采用了端到端 (e2e) ASR 系统，而混合系统在之前的 CHiME 挑战中更为普遍。这种转变主要得益于稳健的大规模预训练模型的可用性，从而降低了 e2e-ASR 的数据负担。

2) 尽管最近在神经语音分离与增强 (SSE) 方面取得了进展，但所有团队仍然严重依赖于有监督的源分离技术，这表明当前的神经 SSE 技术仍无法可靠应对复杂场景和不同的录音设置。

3) 所有最佳系统都采用了目标说话人分离技术来优化说话人分离结果。因此，首次说话人分离中的准确计数至关重要，以避免累积错误，CHiME-8 的 DASR 参与者尤其关注这一部分。

4) 通过会议总结进行的下游评估可能与转录质量弱相关，这是由于大型语言模型在处理错误方面表现出色。在 NOTSOFAR-1 场景中，即使系统的时间受限最小排列 WER 超过 50%，其表现仍可与最有效的系统（约 11%）相媲美。

5) 尽管取得了 recent 进展，但在具有挑战性的声学环境中准确转录自发性语音仍然困难重重，即使采用计算密集型的系统集成也难以例外。

> The CHiME-7 and 8 distant speech recognition (DASR) challenges focus on multi-channel, generalizable, joint automatic speech recognition (ASR) and diarization of conversational speech. With participation from 9 teams submitting 32 diverse systems, these challenges have contributed to state-of-the-art research in the field. This paper outlines the challenges' design, evaluation metrics, datasets, and baseline systems while analyzing key trends from participant submissions. From this analysis it emerges that: 1) Most participants use end-to-end (e2e) ASR systems, whereas hybrid systems were prevalent in previous CHiME challenges. This transition is mainly due to the availability of robust large-scale pre-trained models, which lowers the data burden for e2e-ASR. 2) Despite recent advances in neural speech separation and enhancement (SSE), all teams still heavily rely on guided source separation, suggesting that current neural SSE techniques are still unable to reliably deal with complex scenarios and different recording setups. 3) All best systems employ diarization refinement via target-speaker diarization techniques. Accurate speaker counting in the first diarization pass is thus crucial to avoid compounding errors and CHiME-8 DASR participants especially focused on this part. 4) Downstream evaluation via meeting summarization can correlate weakly with transcription quality due to the remarkable effectiveness of large-language models in handling errors. On the NOTSOFAR-1 scenario, even systems with over 50\% time-constrained minimum permutation WER can perform roughly on par with the most effective ones (around 11\%). 5) Despite recent progress, accurately transcribing spontaneous speech in challenging acoustic environments remains difficult, even when using computationally intensive system ensembles.

[Arxiv](https://arxiv.org/abs/2507.18161)