# 基于大型语言模型与检索增强生成的模型驱动量子代码生成

发布时间：2025年08月27日

`RAG` `基础理论`

> Model-Driven Quantum Code Generation Using Large Language Models and Retrieval-Augmented Generation

# 摘要

> 本文提出了一个全新的研究方向，旨在借助可集成检索增强生成（RAG）管道的大型语言模型（LLMs）实现模型到文本/代码的转换。研究聚焦于量子及混合量子-经典软件系统——在这类系统中，模型驱动方法能有效降低成本，并缓解异构平台环境及开发人员技能不足带来的风险。我们对其中一项提议进行了验证：从软件系统的UML模型实例生成代码。生成的Python代码基于成熟库Qiskit，可在基于门或基于电路的量子计算机上运行。我们部署的RAG管道还整合了公共GitHub仓库中的Qiskit代码样本。实验结果显示，精心设计的提示可将CodeBLEU分数提升高达四倍，产出更精准、一致的量子代码。未来，这一研究方向有望通过进一步实验探索（如将软件系统模型实例作为RAG管道的信息源，或利用LLMs实现代码到代码的转换，例如代码转换用例），解决本文提出的其他研究问题，从而拓展更多可能性。

> This paper introduces a novel research direction for model-to-text/code transformations by leveraging Large Language Models (LLMs) that can be enhanced with Retrieval-Augmented Generation (RAG) pipelines. The focus is on quantum and hybrid quantum-classical software systems, where model-driven approaches can help reduce the costs and mitigate the risks associated with the heterogeneous platform landscape and lack of developers' skills. We validate one of the proposed ideas regarding generating code out of UML model instances of software systems. This Python code uses a well-established library, called Qiskit, to execute on gate-based or circuit-based quantum computers. The RAG pipeline that we deploy incorporates sample Qiskit code from public GitHub repositories. Experimental results show that well-engineered prompts can improve CodeBLEU scores by up to a factor of four, yielding more accurate and consistent quantum code. However, the proposed research direction can go beyond this through further investigation in the future by conducting experiments to address our other research questions and ideas proposed here, such as deploying software system model instances as the source of information in the RAG pipelines, or deploying LLMs for code-to-code transformations, for instance, for transpilation use cases.

[Arxiv](https://arxiv.org/abs/2508.21097)