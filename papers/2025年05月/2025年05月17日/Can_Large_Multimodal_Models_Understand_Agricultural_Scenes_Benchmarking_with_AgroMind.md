# 大型多模态模型能否理解农业场景？通过AgroMind进行基准测试

发布时间：2025年05月17日

`LLM应用`

> Can Large Multimodal Models Understand Agricultural Scenes? Benchmarking with AgroMind

# 摘要

> 大型多模态模型（LMMs）在多个领域展现出强大能力，但在农业遥感（RS）领域的综合性基准测试仍然匮乏。现有针对农业RS场景设计的基准测试存在显著局限性，主要体现在数据集场景多样性不足和任务设计过于简化。为填补这一空白，我们推出了AgroMind，这是一个涵盖空间感知、物体理解、场景理解与场景推理四大任务维度的农业遥感综合性基准测试，总计包含13种任务类型，从作物识别与健康监测到环境分析。我们通过整合八种公开数据集和一个私有农田地块数据集，构建了一个高质量的评测集，包含25,026 个问答对和15,556 张图像。该流程始于多源数据预处理，涵盖数据收集、格式标准化和标注优化。随后，我们通过系统化定义任务，生成了一系列与农业相关的多样化问题。最后，我们采用LMMs进行推理、生成回答并进行详细分析。我们在AgroMind上评估了18个开源LMMs和3个闭源模型。实验结果显示，各模型在空间推理和细粒度识别方面存在显著性能差异，值得注意的是，人类的表现落后于多个领先的LMMs。通过建立农业RS的标准评测框架，AgroMind揭示了LMMs在领域知识上的局限性，并为未来研究指明了关键挑战。数据和代码可在https://rssysu.github.io/AgroMind/获取。

> Large Multimodal Models (LMMs) has demonstrated capabilities across various domains, but comprehensive benchmarks for agricultural remote sensing (RS) remain scarce. Existing benchmarks designed for agricultural RS scenarios exhibit notable limitations, primarily in terms of insufficient scene diversity in the dataset and oversimplified task design. To bridge this gap, we introduce AgroMind, a comprehensive agricultural remote sensing benchmark covering four task dimensions: spatial perception, object understanding, scene understanding, and scene reasoning, with a total of 13 task types, ranging from crop identification and health monitoring to environmental analysis. We curate a high-quality evaluation set by integrating eight public datasets and one private farmland plot dataset, containing 25,026 QA pairs and 15,556 images. The pipeline begins with multi-source data preprocessing, including collection, format standardization, and annotation refinement. We then generate a diverse set of agriculturally relevant questions through the systematic definition of tasks. Finally, we employ LMMs for inference, generating responses, and performing detailed examinations. We evaluated 18 open-source LMMs and 3 closed-source models on AgroMind. Experiments reveal significant performance gaps, particularly in spatial reasoning and fine-grained recognition, it is notable that human performance lags behind several leading LMMs. By establishing a standardized evaluation framework for agricultural RS, AgroMind reveals the limitations of LMMs in domain knowledge and highlights critical challenges for future work. Data and code can be accessed at https://rssysu.github.io/AgroMind/.

[Arxiv](https://arxiv.org/abs/2505.12207)