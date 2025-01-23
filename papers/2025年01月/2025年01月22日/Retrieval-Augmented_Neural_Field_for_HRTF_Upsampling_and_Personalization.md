# # 检索增强神经场：HRTF上采样与个性化

发布时间：2025年01月22日

`RAG

理由：这篇论文提出了检索增强神经场（RANF），通过从数据集中检索与目标受试者HRTFs相近的受试者，并将检索到的信息输入神经场来生成沉浸式双耳音频。这种方法结合了检索和神经场技术，属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴。` `音频处理` `虚拟现实`

> Retrieval-Augmented Neural Field for HRTF Upsampling and Personalization

# 摘要

> # 摘要
为了生成沉浸式双耳音频，密集空间网格的头相关传递函数（HRTFs）是必不可少的，但其记录过程耗时较长。尽管基于神经场的HRTF空间上采样已取得显著进展，但从少数测量方向（如3或5个点）进行上采样仍具挑战性。为此，我们提出了检索增强神经场（RANF）。RANF从数据集中检索出与目标受试者HRTFs相近的受试者，并将检索到的受试者在目标方向的HRTF与声源方向一同输入神经场。此外，我们设计了一种神经网络，能够高效处理多个检索到的受试者，灵感来自变换-平均-连接的多通道处理技术。实验表明，RANF在SONICOM数据集上表现出色，并成为2024年听众声学个性化挑战赛任务2获胜方案的核心组件。

> Head-related transfer functions (HRTFs) with dense spatial grids are desired for immersive binaural audio generation, but their recording is time-consuming. Although HRTF spatial upsampling has shown remarkable progress with neural fields, spatial upsampling only from a few measured directions, e.g., 3 or 5 measurements, is still challenging. To tackle this problem, we propose a retrieval-augmented neural field (RANF). RANF retrieves a subject whose HRTFs are close to those of the target subject from a dataset. The HRTF of the retrieved subject at the desired direction is fed into the neural field in addition to the sound source direction itself. Furthermore, we present a neural network that can efficiently handle multiple retrieved subjects, inspired by a multi-channel processing technique called transform-average-concatenate. Our experiments confirm the benefits of RANF on the SONICOM dataset, and it is a key component in the winning solution of Task 2 of the listener acoustic personalization challenge 2024.

[Arxiv](https://arxiv.org/abs/2501.13017)