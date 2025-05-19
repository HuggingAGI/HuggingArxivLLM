# # HumaniBench：一个以人类为中心的大型多模态模型评估框架

发布时间：2025年05月16日

`其他` `人工智能伦理` `以人为中心的人工智能`

> HumaniBench: A Human-Centric Framework for Large Multimodal Models Evaluation

# 摘要

> # 摘要
大型多模态模型（LMMs）在视觉语言任务中表现优异，但在公平性、伦理、共情和包容性等人本标准上仍存在不足，这些标准对实现与人类价值观的对齐至关重要。我们推出HumaniBench，一个包含32,000个真实世界图像-问题配对的综合性基准测试，通过可扩展的GPT-4辅助流水线进行标注，并由领域专家全面验证。

HumaniBench评估了以人为中心的人工智能（HCAI）的七大原则：公平性、伦理、理解力、推理、语言包容性、共情和稳健性，涵盖七大多样化任务，包括开放和封闭式视觉问答（VQA）、多语言问答、视觉定位、共情描述和稳健性测试。通过对15种先进LMM（开源与闭源）的基准测试发现，专有模型总体表现领先，但在稳健性和视觉定位方面仍存在弱点。部分开源模型在平衡准确性和对人类价值观的对齐方面也面临挑战。

作为首个专为HCAI原则设计的基准测试，HumaniBench提供了一个严格的测试环境，用于诊断对齐差距并引导LMMs朝着既准确又具有社会责任感的行为发展。数据集、标注提示和评估代码可在以下链接获取：https://vectorinstitute.github.io/HumaniBench

> Large multimodal models (LMMs) now excel on many vision language benchmarks, however, they still struggle with human centered criteria such as fairness, ethics, empathy, and inclusivity, key to aligning with human values. We introduce HumaniBench, a holistic benchmark of 32K real-world image question pairs, annotated via a scalable GPT4o assisted pipeline and exhaustively verified by domain experts. HumaniBench evaluates seven Human Centered AI (HCAI) principles: fairness, ethics, understanding, reasoning, language inclusivity, empathy, and robustness, across seven diverse tasks, including open and closed ended visual question answering (VQA), multilingual QA, visual grounding, empathetic captioning, and robustness tests. Benchmarking 15 state of the art LMMs (open and closed source) reveals that proprietary models generally lead, though robustness and visual grounding remain weak points. Some open-source models also struggle to balance accuracy with adherence to human-aligned principles. HumaniBench is the first benchmark purpose built around HCAI principles. It provides a rigorous testbed for diagnosing alignment gaps and guiding LMMs toward behavior that is both accurate and socially responsible. Dataset, annotation prompts, and evaluation code are available at: https://vectorinstitute.github.io/HumaniBench

[Arxiv](https://arxiv.org/abs/2505.11454)