# 针对不同输入音频表示的语音识别的后期融合集成体

发布时间：2024年12月01日

`其他` `语音识别` `音频处理`

> Late fusion ensembles for speech recognition on diverse input audio representations

# 摘要

> 我们探究了语音音频的多样表示形式，及其对应用于自动语音识别（ASR）任务的 E-Branchformer 模型的后期融合集成性能的影响。虽说大家都知道集成方法通常能提升系统性能，哪怕是在语音识别方面，但研究像中型和大型 E-Branchformer 这类复杂先进模型的集成在基础模型基于输入语音音频的多种表示形式训练时，在这种情况下的应对方式，是饶有趣味的。在四个常用的基准数据集	extit{Librispeech、Aishell、Gigaspeech}、	extit{TEDLIUMv2}上评估结果表明，相较于在这些数据集上使用类似技术训练的最先进模型，仍能实现 1％ - 14％ 的改进。值得一提的是，即便使用语言模型，这种集成也能带来改进，只是差距在逐渐缩小。

> We explore diverse representations of speech audio, and their effect on a performance of late fusion ensemble of E-Branchformer models, applied to Automatic Speech Recognition (ASR) task. Although it is generally known that ensemble methods often improve the performance of the system even for speech recognition, it is very interesting to explore how ensembles of complex state-of-the-art models, such as medium-sized and large E-Branchformers, cope in this setting when their base models are trained on diverse representations of the input speech audio. The results are evaluated on four widely-used benchmark datasets: \textit{Librispeech, Aishell, Gigaspeech}, \textit{TEDLIUMv2} and show that improvements of $1\% - 14\%$ can still be achieved over the state-of-the-art models trained using comparable techniques on these datasets. A noteworthy observation is that such ensemble offers improvements even with the use of language models, although the gap is closing.

[Arxiv](https://arxiv.org/abs/2412.01861)