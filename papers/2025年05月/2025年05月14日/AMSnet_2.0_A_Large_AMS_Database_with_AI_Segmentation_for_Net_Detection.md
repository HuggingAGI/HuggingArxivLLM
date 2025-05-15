# AMSnet 2.0：结合 AI 分割技术的大型 AMS 数据库，专为网络检测打造

发布时间：2025年05月14日

`LLM应用` `电子设计自动化` `电路设计`

> AMSnet 2.0: A Large AMS Database with AI Segmentation for Net Detection

# 摘要

> 现有的多模态大型语言模型（MLLMs）在理解电路图方面表现欠佳，这主要是因为缺乏高质量的电路图-网表训练数据。目前的工作如AMSnet通过电路图解析生成网表，但这些方法依赖硬编码的启发式规则，难以处理复杂或嘈杂的电路图。因此，我们提出了一种基于高鲁棒性分割的新颖网检测机制。该方法不仅恢复了位置信息，还实现了电路图的数字重建。我们进一步扩展了AMSnet数据集，整合了来自多个来源的电路图图像，打造了AMSnet 2.0。新版本包含了2,686个电路的完整信息，包括电路图图像、Spectre格式的网表、OpenAccess数字电路图以及电路元件和网的位置信息，而原始的AMSnet仅包含792个电路的SPICE网表，且缺乏数字电路图支持。

> Current multimodal large language models (MLLMs) struggle to understand circuit schematics due to their limited recognition capabilities. This could be attributed to the lack of high-quality schematic-netlist training data. Existing work such as AMSnet applies schematic parsing to generate netlists. However, these methods rely on hard-coded heuristics and are difficult to apply to complex or noisy schematics in this paper. We therefore propose a novel net detection mechanism based on segmentation with high robustness. The proposed method also recovers positional information, allowing digital reconstruction of schematics. We then expand AMSnet dataset with schematic images from various sources and create AMSnet 2.0. AMSnet 2.0 contains 2,686 circuits with schematic images, Spectre-formatted netlists, OpenAccess digital schematics, and positional information for circuit components and nets, whereas AMSnet only includes 792 circuits with SPICE netlists but no digital schematics.

[Arxiv](https://arxiv.org/abs/2505.09155)