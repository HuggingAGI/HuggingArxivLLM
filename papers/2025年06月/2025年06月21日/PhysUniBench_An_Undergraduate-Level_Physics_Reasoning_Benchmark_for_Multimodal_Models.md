# PhysUniBench：一个多模态模型的本科物理推理能力评估基准

发布时间：2025年06月21日

`LLM应用` `物理科学`

> PhysUniBench: An Undergraduate-Level Physics Reasoning Benchmark for Multimodal Models

# 摘要

> 物理问题解决对大型AI模型而言是一大挑战，需整合概念理解、数学推理及物理图解解读。现有评估方法在捕捉大学物理的广度与复杂性上存在明显局限，凸显了对更严格评估的需求。为此，我们推出PhysUniBench——一个专为评估和提升多模态大型语言模型（MLLMs）在大学物理问题上推理能力而设计的大规模多模态基准测试。PhysUniBench包含3,304个物理问题，覆盖物理学8大主要分支，每题均配有视觉图解。该基准测试包含开放性和选择题，通过迭代的模型在环过程系统整理和难度评级。其构建涉及严格的多阶段流程，包括多次迭代、专家评估、自动过滤易解问题，以及包含五个级别的精细难度分级系统。实验表明，当前最先进的模型在物理推理上面临重大挑战。例如，GPT-4o mini在PhysUniBench中的准确率仅为约34.2%。这些结果表明，现有MLLMs在高级物理推理，尤其是多步骤问题和需精准图解解读的问题上存在困难。通过提供一个广泛且严格的评估工具，PhysUniBench旨在推动AI在科学领域的发展，促进具备更强物理推理能力、问题解决技巧和多模态理解能力的模型开发。该基准测试和评估脚本可在https://prismax-team.github.io/PhysUniBenchmark/获取。


> Physics problem-solving is a challenging domain for large AI models, requiring integration of conceptual understanding, mathematical reasoning, and interpretation of physical diagrams. Current evaluation methodologies show notable limitations in capturing the breadth and complexity of undergraduate-level physics, underscoring the need for more rigorous assessments. To this end, we present PhysUniBench, a large-scale multimodal benchmark designed to evaluate and improve the reasoning capabilities of multimodal large language models (MLLMs) specifically on undergraduate-level physics problems. PhysUniBench consists of 3,304 physics questions spanning 8 major sub-disciplines of physics, each accompanied by one visual diagrams. The benchmark includes both open-ended and multiple-choice questions, systematically curated and difficulty-rated through an iterative model-in-the-loop process. The benchmark's construction involved a rigorous multi-stage process, including multiple roll-outs, expert-level evaluation, automated filtering of easily solved problems, and a nuanced difficulty grading system with five levels. Through extensive experiments, we observe that current state-of-the-art models encounter substantial challenges in physics reasoning. For example, GPT-4o mini achieves only about 34.2\% accuracy in the proposed PhysUniBench. These results highlight that current MLLMs struggle with advanced physics reasoning, especially on multi-step problems and those requiring precise diagram interpretation. By providing a broad and rigorous assessment tool, PhysUniBench aims to drive progress in AI for Science, encouraging the development of models with stronger physical reasoning, problem-solving skills, and multimodal understanding. The benchmark and evaluation scripts are available at https://prismax-team.github.io/PhysUniBenchmark/.

[Arxiv](https://arxiv.org/abs/2506.17667)