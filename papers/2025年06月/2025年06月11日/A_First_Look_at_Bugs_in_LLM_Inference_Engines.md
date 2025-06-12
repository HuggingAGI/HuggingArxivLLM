# 初探大语言模型推理引擎中的漏洞

发布时间：2025年06月11日

`LLM应用

LLM应用` `人工智能` `软件工程`

> A First Look at Bugs in LLM Inference Engines

# 摘要

> 大型语言模型专用推理引擎（简称\emph{LLM推理引擎}）已经成为现代AI基础设施中的核心组件，支持基于LLM的应用程序（LLM应用）在云端和本地设备上的部署。尽管推理引擎在AI基础设施中扮演着关键角色，但由于LLM对资源的巨大需求以及跨平台兼容性的复杂性，这些引擎容易出现bug。然而，系统性地理解这些bug的机制仍然存在空白。为了填补这一空白，我们首次针对LLM推理引擎中的bug展开实证研究。我们从5个广泛应用的LLM推理引擎的官方仓库中挖掘数据，构建了一个包含929个真实世界bug的综合数据集。通过严格的开放编码过程，我们对这些bug进行了深入分析，揭示了它们的症状、根本原因以及普遍性。我们的研究发现，LLM推理引擎中存在六大类bug症状，并归纳出28种根本原因的分类体系，为理解LLM推理引擎中bug检测与定位的关键挑战提供了重要启示。基于这些发现，我们为研究人员、推理引擎供应商以及LLM应用开发者提出了切实可行的实践建议。

> Large language model-specific inference engines (in short as \emph{LLM inference engines}) have become a fundamental component of modern AI infrastructure, enabling the deployment of LLM-powered applications (LLM apps) across cloud and local devices. Despite their critical role, LLM inference engines are prone to bugs due to the immense resource demands of LLMs and the complexities of cross-platform compatibility. However, a systematic understanding of these bugs remains lacking. To bridge this gap, we present the first empirical study on bugs in LLM inference engines. We mine official repositories of 5 widely adopted LLM inference engines, constructing a comprehensive dataset of 929 real-world bugs. Through a rigorous open coding process, we analyze these bugs to uncover their symptoms, root causes, and commonality. Our findings reveal six major bug symptoms and a taxonomy of 28 root causes, shedding light on the key challenges in bug detection and location within LLM inference engines. Based on these insights, we propose a series of actionable implications for researchers, inference engine vendors, and LLM app developers.

[Arxiv](https://arxiv.org/abs/2506.09713)