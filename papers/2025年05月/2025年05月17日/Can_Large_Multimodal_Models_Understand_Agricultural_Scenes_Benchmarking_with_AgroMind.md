# 大型多模态模型能否理解农业场景？用AgroMind探索其能力边界

发布时间：2025年05月17日

`LLM应用

理由：该论文主要探讨了大型多模态模型（LMMs）在农业遥感领域的应用，提出了一个综合性的基准测试AgroMind，并评估了多种模型的性能。这属于将LMMs应用于特定领域的研究，因此归类为LLM应用。`

> Can Large Multimodal Models Understand Agricultural Scenes? Benchmarking with AgroMind

# 摘要

> 大型多模态模型（LMMs）在多个领域展现出卓越的能力，但在农业遥感（RS）领域，综合性基准测试仍显匮乏。现有针对农业遥感场景设计的基准测试存在明显局限，主要体现在数据集场景多样性不足和任务设计过于简化。为填补这一空白，我们推出了AgroMind，一个全面的农业遥感基准测试，涵盖空间感知、目标理解、场景理解和场景推理四大任务维度，共包含13种任务类型，从作物识别和健康监测到环境分析。我们通过整合八种公开数据集和一种私人农田地块数据集，构建了一个高质量的评估集，包含25,026个问答对和15,556张图像。流程始于多源数据预处理，包括数据收集、格式标准化和标注优化。随后，我们通过系统化定义任务，生成一系列与农业相关的多样化问题。最后，我们运用LMMs进行推理、生成回答并进行详细分析。我们在AgroMind上评估了18种开源LMMs和3种闭源模型。实验结果揭示了显著的性能差距，特别是在空间推理和细粒度识别方面，值得注意的是，人类的表现落后于几种领先的LMMs。通过为农业遥感建立标准化的评估框架，AgroMind揭示了LMMs在领域知识方面的局限性，并突出了未来研究的关键挑战。数据和代码可在https://rssysu.github.io/AgroMind/获取。

> Large Multimodal Models (LMMs) has demonstrated capabilities across various domains, but comprehensive benchmarks for agricultural remote sensing (RS) remain scarce. Existing benchmarks designed for agricultural RS scenarios exhibit notable limitations, primarily in terms of insufficient scene diversity in the dataset and oversimplified task design. To bridge this gap, we introduce AgroMind, a comprehensive agricultural remote sensing benchmark covering four task dimensions: spatial perception, object understanding, scene understanding, and scene reasoning, with a total of 13 task types, ranging from crop identification and health monitoring to environmental analysis. We curate a high-quality evaluation set by integrating eight public datasets and one private farmland plot dataset, containing 25,026 QA pairs and 15,556 images. The pipeline begins with multi-source data preprocessing, including collection, format standardization, and annotation refinement. We then generate a diverse set of agriculturally relevant questions through the systematic definition of tasks. Finally, we employ LMMs for inference, generating responses, and performing detailed examinations. We evaluated 18 open-source LMMs and 3 closed-source models on AgroMind. Experiments reveal significant performance gaps, particularly in spatial reasoning and fine-grained recognition, it is notable that human performance lags behind several leading LMMs. By establishing a standardized evaluation framework for agricultural RS, AgroMind reveals the limitations of LMMs in domain knowledge and highlights critical challenges for future work. Data and code can be accessed at https://rssysu.github.io/AgroMind/.

[Arxiv](https://arxiv.org/abs/2505.12207)