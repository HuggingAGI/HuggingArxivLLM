# 从基础规范到复杂场景：本科热力学中大型语言模型能力评估

发布时间：2025年08月29日

`LLM应用` `教育科技`

> From Canonical to Complex: Benchmarking LLM Capabilities in Undergraduate Thermodynamics

# 摘要

> 大型语言模型（LLMs）在科学教育中日益被视作辅导工具，但其能否在本科教学中独立使用仍存疑——毕竟可靠的教学不仅需要流畅的知识回忆，更依赖连贯且基于原理的推理。热力学定律简洁却内涵丰富，在状态函数与路径函数、可逆性及熵等概念间存在细微差异，恰好为评估这些能力提供了理想场景。为此，我们构建了UTQA——一个包含50道题的本科热力学问答基准，涵盖理想气体过程、可逆性及图表解读。2025年主流模型均未达到我们设定的95%能力阈值：表现最佳的LLM准确率为82%，纯文本题目表现优于图像推理题（后者正确率常接近随机水平）。提示词措辞和句法复杂度与模型表现的相关性较低，主要短板体现在有限速率/不可逆场景的处理，以及将视觉特征与热力学意义关联的能力上，这表明当前LLM尚未具备在该领域独立辅导的能力。

> Large language models (LLMs) are increasingly considered as tutoring aids in science education. Yet their readiness for unsupervised use in undergraduate instruction remains uncertain, as reliable teaching requires more than fluent recall: it demands consistent, principle-grounded reasoning. Thermodynamics, with its compact laws and subtle distinctions between state and path functions, reversibility, and entropy, provides an ideal testbed for evaluating such capabilities. Here we present UTQA, a 50-item undergraduate thermodynamics question answering benchmark, covering ideal-gas processes, reversibility, and diagram interpretation. No leading 2025-era model exceeded our 95\% competence threshold: the best LLMs achieved 82\% accuracy, with text-only items performing better than image reasoning tasks, which often fell to chance levels. Prompt phrasing and syntactic complexity showed modest to little correlation with performance. The gap concentrates in finite-rate/irreversible scenarios and in binding visual features to thermodynamic meaning, indicating that current LLMs are not yet suitable for unsupervised tutoring in this domain.

[Arxiv](https://arxiv.org/abs/2508.21452)