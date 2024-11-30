# 本研究探讨将大型语言模型应用于时间序列物理传感数据的虚拟标注任务，以评估其作为有效标注工具的能力。

发布时间：2024年03月02日

`LLM应用`

> Evaluating Large Language Models as Virtual Annotators for Time-series Physical Sensing Data

# 摘要

> 在对惯性数据等时间序列数据的传统人机交互式标注过程中，往往需借助环境中的视频或音频等辅助模态信息来辅助人工标注，原因是原始数值数据即便对专家而言也过于晦涩难解。尽管如此，这种方法仍面临高昂成本、效率低下、额外模态存储、耗时、扩展性受限及隐私问题等诸多困扰。值得注意的是，最新的大型语言模型（LLMs）经过大量公开字母数字数据训练，不仅擅长自然语言处理任务，还能理解并处理更多类型的数据。由此引出了一个潜在思路：将 LLMS 当作虚拟标注员，直接向其输入原始传感器数据完成标注工作，从而绕过对其他模态的依赖，有效解决传统人机交互式标注的难题。受此启发，本文展开深入研究，旨在探究当前最先进（SOTA）的 LLMs 是否可用于标注时间序列物理传感数据。为确保研究的严谨性，我们将研究过程划分为两大步骤。首先，我们剖析了像 GPT-4 这样的 LLM 在解读原始传感器数据时遭遇的困难；随后，在第二步中，根据第一步得到的观察结果，我们研究如何运用前沿的自监督学习（SSL）技术对原始传感器数据进行编码，并借助转换后的时间序列数据引导 LLM 进行标注输出。通过在四个典型人体活动识别（HAR）数据集上的详尽评估显示，结合 SSL 编码和基于度量的指导手段，能让 LLM 更理性地做出判断，并在无需复杂的微调或精心设计的提示情况下，也能为传感数据提供精准标注。

> Traditional human-in-the-loop-based annotation for time-series data like inertial data often requires access to alternate modalities like video or audio from the environment. These alternate sources provide the necessary information to the human annotator, as the raw numeric data is often too obfuscated even for an expert. However, this traditional approach has many concerns surrounding overall cost, efficiency, storage of additional modalities, time, scalability, and privacy. Interestingly, recent large language models (LLMs) are also trained with vast amounts of publicly available alphanumeric data, which allows them to comprehend and perform well on tasks beyond natural language processing. Naturally, this opens up a potential avenue to explore LLMs as virtual annotators where the LLMs will be directly provided the raw sensor data for annotation instead of relying on any alternate modality. Naturally, this could mitigate the problems of the traditional human-in-the-loop approach. Motivated by this observation, we perform a detailed study in this paper to assess whether the state-of-the-art (SOTA) LLMs can be used as virtual annotators for labeling time-series physical sensing data. To perform this in a principled manner, we segregate the study into two major phases. In the first phase, we investigate the challenges an LLM like GPT-4 faces in comprehending raw sensor data. Considering the observations from phase 1, in the next phase, we investigate the possibility of encoding the raw sensor data using SOTA SSL approaches and utilizing the projected time-series data to get annotations from the LLM. Detailed evaluation with four benchmark HAR datasets shows that SSL-based encoding and metric-based guidance allow the LLM to make more reasonable decisions and provide accurate annotations without requiring computationally expensive fine-tuning or sophisticated prompt engineering.

[Arxiv](https://arxiv.org/abs/2403.01133)