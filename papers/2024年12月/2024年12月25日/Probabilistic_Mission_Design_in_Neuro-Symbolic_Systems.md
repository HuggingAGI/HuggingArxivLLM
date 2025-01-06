# 神经符号系统中的概率任务设计

发布时间：2024年12月25日

`Agent

理由：这篇论文主要讨论了一种结合概率与神经符号的架构，用于智能车辆导航中的法律概念和限制建模，并处理不确定的空间关系和噪声感知。该系统架构通过混合概率逻辑程序（HPLP）将地理空间和感官数据与代理的状态空间及其合法性推理相结合，生成概率任务景观（PML）。此外，论文还提到将该系统与大型语言模型（LLM）和基于Transformer的视觉模型集成。这些内容表明，论文的核心是设计和实现一个智能代理系统，用于处理复杂的导航任务和法律推理，因此应归类为Agent。` `空中交通`

> Probabilistic Mission Design in Neuro-Symbolic Systems

# 摘要

> # 摘要
先进空中交通（AAM）是一个快速发展的领域，要求对智能车辆导航中的法律概念和限制进行精确建模。同时，AAM的实施必须稳健应对人类居住空间固有的动态性和不确定性。超视距（BVLOS）无人飞行器系统（UAS）的应用则有望大幅提升物流和应急响应能力。为此，我们提出了一种概率与神经符号结合的架构，以可解释和适应性的方式编码法律框架和专家知识，处理不确定的空间关系和噪声感知。具体来说，我们展示了概率任务设计（ProMis），该系统架构通过混合概率逻辑程序（HPLP）将地理空间和感官数据与代理的状态空间及其合法性推理相结合，生成概率任务景观（PML），量化代理在导航空间中满足任务条件的信念。我们进一步扩展了ProMis的推理能力，并将其与大型语言模型（LLM）和基于Transformer的视觉模型等强大机器学习模型集成。实验表明，ProMis在多模态输入数据中的应用广泛适用于多种重要的AAM场景。

> Advanced Air Mobility (AAM) is a growing field that demands accurate modeling of legal concepts and restrictions in navigating intelligent vehicles. In addition, any implementation of AAM needs to face the challenges posed by inherently dynamic and uncertain human-inhabited spaces robustly. Nevertheless, the employment of Unmanned Aircraft Systems (UAS) beyond visual line of sight (BVLOS) is an endearing task that promises to enhance significantly today's logistics and emergency response capabilities. To tackle these challenges, we present a probabilistic and neuro-symbolic architecture to encode legal frameworks and expert knowledge over uncertain spatial relations and noisy perception in an interpretable and adaptable fashion. More specifically, we demonstrate Probabilistic Mission Design (ProMis), a system architecture that links geospatial and sensory data with declarative, Hybrid Probabilistic Logic Programs (HPLP) to reason over the agent's state space and its legality. As a result, ProMis generates Probabilistic Mission Landscapes (PML), which quantify the agent's belief that a set of mission conditions is satisfied across its navigation space. Extending prior work on ProMis' reasoning capabilities and computational characteristics, we show its integration with potent machine learning models such as Large Language Models (LLM) and Transformer-based vision models. Hence, our experiments underpin the application of ProMis with multi-modal input data and how our method applies to many important AAM scenarios.

[Arxiv](https://arxiv.org/abs/2501.01439)