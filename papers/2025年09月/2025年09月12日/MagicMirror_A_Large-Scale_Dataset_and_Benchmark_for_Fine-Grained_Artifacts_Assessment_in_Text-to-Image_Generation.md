# MagicMirror：面向文本到图像生成中细粒度伪影评估的大规模数据集与基准

发布时间：2025年09月12日

`LLM应用` `媒体与娱乐`

> MagicMirror: A Large-Scale Dataset and Benchmark for Fine-Grained Artifacts Assessment in Text-to-Image Generation

# 摘要

> 文本到图像（T2I）生成在指令遵循和美学呈现上已取得显著进步。然而，物理伪影（如解剖结构缺陷）的普遍存在仍是一大难题，它们严重影响感知质量，限制实际应用。由于这些伪影多样且复杂，亟需一套系统、细粒度的评估框架，但现有基准测试中尚无此类框架。为此，我们提出MagicMirror——一个全面的伪影评估框架，以填补这一空白。我们首先构建了生成图像伪影的详细分类体系，在其指导下手动标注了MagicData340K数据集——这是首个含34万张生成图像的大规模人工标注数据集，每张图像均带有细粒度伪影标签。基于该数据集，我们训练出MagicAssessor——一个能提供详细评估及对应标签的视觉语言模型（VLM）。为解决类别不平衡、奖励黑客等问题，我们设计了全新的数据采样策略，并为组相对策略优化（GRPO）构建了多级奖励机制。最后，我们借助MagicAssessor构建了MagicBench——一个用于评估当前T2I模型图像伪影的自动化基准测试工具。通过MagicBench评估发现，尽管顶级模型（如GPT-image-1）已被广泛应用，但仍普遍存在严重伪影问题，这表明减少伪影是未来T2I发展的核心方向。项目页面：https://wj-inf.github.io/MagicMirror-page/。

> Text-to-image (T2I) generation has achieved remarkable progress in instruction following and aesthetics. However, a persistent challenge is the prevalence of physical artifacts, such as anatomical and structural flaws, which severely degrade perceptual quality and limit application. Given the diversity and complexity of these artifacts, a systematic and fine-grained evaluation framework is required, which is lacking in current benchmarks. To fill this gap, we introduce MagicMirror, a comprehensive framework for artifacts assessment. We first establish a detailed taxonomy of generated image artifacts. Guided by this taxonomy, we manually annotate MagicData340K, the first human-annotated large-scale dataset of 340K generated images with fine-grained artifact labels. Building on this dataset, we train MagicAssessor, a Vision-Language Model (VLM) that provides detailed assessments and corresponding labels. To overcome challenges like class imbalance and reward hacking, we design a novel data sampling strategy and a multi-level reward system for Group Relative Policy Optimization (GRPO). Finally, we leverage MagicAssessor to construct MagicBench, an automated benchmark for evaluating the image artifacts of current T2I models. Our evaluation with MagicBench reveals that despite their widespread adoption, even top-tier models like GPT-image-1 are consistently plagued by significant artifacts, highlighting artifact reduction as a critical frontier for future T2I development. Project page: https://wj-inf.github.io/MagicMirror-page/.

[Arxiv](https://arxiv.org/abs/2509.10260)