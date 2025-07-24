# 见林又见木：知识驱动的视觉问答协同推理框架

发布时间：2025年07月23日

`LLM应用` `视觉问答` `计算机视觉`

> See the Forest and the Trees: A Synergistic Reasoning Framework for Knowledge-Based Visual Question Answering

# 摘要

> 多模态大型语言模型（MLLMs）在知识型视觉问答（KBVQA）领域推动了前沿发展，但其推理能力从根本上受限于对单一维度证据的依赖。这种“只见树木，不见森林”的方法阻碍了稳健、多方面的理解。受“既见森林又见树木”原则的启发，我们提出了Synergos-VQA，一种新颖的协同推理框架。Synergos-VQA在推理过程中同时生成并融合三条互补的证据流：(1) 整体证据以感知整个场景（“森林”），(2) 来自原型驱动模块的结构证据以识别关键对象（“树木”），以及(3) 来自反事实探针的因果证据以确保推理的稳健基础。通过协同融合这些多方面的证据，我们的框架实现了更加全面和可靠的推理过程。大量实验表明，Synergos-VQA在包括OK-VQA和A-OKVQA在内的三个具有挑战性的基准测试中一举确立了新的标杆。此外，我们的方法展示了强大的即插即用能力，显著提升了各种开源MLLMs的性能，证明了卓越的方法设计能够超越单纯的模型规模优势。

> Multimodal Large Language Models (MLLMs) have pushed the frontiers of Knowledge-Based Visual Question Answering (KBVQA), yet their reasoning is fundamentally bottlenecked by a reliance on uni-dimensional evidence. This "seeing only the trees, but not the forest" approach prevents robust, multi-faceted understanding. Inspired by the principle of seeing both the forest and trees, we propose Synergos-VQA, a novel synergistic reasoning framework. At its core, Synergos-VQA concurrently generates and fuses three complementary evidence streams at inference time: (1) Holistic Evidence to perceive the entire scene (the "forest"), (2) Structural Evidence from a prototype-driven module to identify key objects (the "trees"), and (3) Causal Evidence from a counterfactual probe to ensure the reasoning is robustly grounded. By synergistically fusing this multi-faceted evidence, our framework achieves a more comprehensive and reliable reasoning process. Extensive experiments show that Synergos-VQA decisively establishes a new state-of-the-art on three challenging benchmarks, including OK-VQA and A-OKVQA. Furthermore, our approach demonstrates strong plug-and-play capabilities, significantly boosting various open-source MLLMs and proving that superior methodological design can outperform sheer model scale.

[Arxiv](https://arxiv.org/abs/2507.17659)