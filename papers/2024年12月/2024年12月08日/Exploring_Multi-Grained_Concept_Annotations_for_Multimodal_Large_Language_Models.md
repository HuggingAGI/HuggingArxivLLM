# 探索多模态大型语言模型的多粒度概念标注

发布时间：2024年12月08日

`LLM应用` `多模态` `语言模型`

> Exploring Multi-Grained Concept Annotations for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）仅依靠在粗粒度概念注释（如图像标题）上的预训练，就在视觉-语言任务中表现卓越。我们推测，整合细粒度概念注释（比如对象标签和对象区域）会进一步提升性能，因为这两种数据粒度在概念表征的广度和深度上互为补充。我们为 MLLMs 引入了带有多模态多粒度概念注释（MMGiC）的新数据集。构建 MMGiC 时，我们探究了不同数据配方对多模态理解与生成的影响。分析表明，在结构化模板和通用 MLLM 框架下，多粒度概念注释相互融合与补充。我们清晰地探索并展现了 MMGiC 助力 MLLMs 更好地定位和学习概念，在多个粒度上实现视觉和语言对齐的潜力。我们通过考察 MMGiC 与图像-标题数据在 12 个多模态理解和生成基准上的公平比较及有效协作，进一步验证了我们的假设，比如它们恰当组合在 POPE 和 SEED-Bench 上分别比仅用图像-标题数据实现了 3.95％和 2.34％的绝对提升。代码、数据和模型可在 https://github.com/LooperXX/MMGiC 获取。

> Multimodal Large Language Models (MLLMs) excel in vision--language tasks by pre-training solely on coarse-grained concept annotations (e.g., image captions). We hypothesize that integrating fine-grained concept annotations (e.g., object labels and object regions) will further improve performance, as both data granularities complement each other in terms of breadth and depth in concept representation. We introduce a new dataset featuring Multimodal Multi-Grained Concept annotations (MMGiC) for MLLMs. In constructing MMGiC, we explore the impact of different data recipes on multimodal comprehension and generation. Our analyses reveal that multi-grained concept annotations integrate and complement each other, under our structured template and a general MLLM framework. We clearly explore and demonstrate the potential of MMGiC to help MLLMs better locate and learn concepts, aligning vision and language at multiple granularities. We further validate our hypothesis by investigating the fair comparison and effective collaboration between MMGiC and image--caption data on 12 multimodal comprehension and generation benchmarks, e.g., their appropriate combination achieve 3.95% and 2.34% absolute improvements over image--caption data alone on POPE and SEED-Bench. Code, data and models will be available at https://github.com/LooperXX/MMGiC.

[Arxiv](https://arxiv.org/abs/2412.05939)