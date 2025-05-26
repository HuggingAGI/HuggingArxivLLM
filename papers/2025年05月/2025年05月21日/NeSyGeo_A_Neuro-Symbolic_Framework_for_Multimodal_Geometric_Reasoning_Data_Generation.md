# NeSyGeo：一个用于多模态几何推理数据生成的神经符号框架

发布时间：2025年05月21日

`LLM应用`

> NeSyGeo: A Neuro-Symbolic Framework for Multimodal Geometric Reasoning Data Generation

# 摘要

> 提升多模态大型语言模型（MLLMs）的几何推理能力，获取大规模、高质量且具有推理路径的数据至关重要。然而，现有的数据生成方法，无论是基于预定义模板还是受限的符号证明器，都不可避免地面临多样性和数值泛化能力的局限。为此，我们提出了NeSyGeo，一个用于生成几何推理数据的新颖神经符号框架。

首先，我们提出了一种基于实体-关系-约束范式的领域特定语言，以全面表示平面几何的所有组件，并在该符号空间内定义了生成动作。随后，我们设计了一个符号-视觉-文本管道，用于合成符号序列，将其映射到相应的视觉和文本表示，并利用大型语言模型（LLMs）生成多样化的问答（Q&A）对。据我们所知，我们是第一个提出神经符号方法来生成多模态推理数据的研究。

基于此框架，我们构建了包含10万样本的NeSyGeo-CoT和NeSyGeo-Caption数据集，并发布了一个新的基准测试集NeSyGeo-Test，用于评估MLLMs的几何推理能力。实验表明，我们的方法在强化学习和监督微调两种模式下，显著且一致地提升了多个MLLMs的性能。

仅使用4千个样本和两个轮次的强化微调，基础模型在MathVision上的性能提升了+15.8%，在MathVerse上提升了+8.4%，在GeoQA上提升了+7.3%。更值得注意的是，一个4B参数量的模型通过这种微调，其在几何推理任务上的表现甚至可以超越同一系列的8B模型。


> Obtaining large-scale, high-quality data with reasoning paths is crucial for improving the geometric reasoning capabilities of multi-modal large language models (MLLMs). However, existing data generation methods, whether based on predefined templates or constrained symbolic provers, inevitably face diversity and numerical generalization limitations. To address these limitations, we propose NeSyGeo, a novel neuro-symbolic framework for generating geometric reasoning data. First, we propose a domain-specific language grounded in the entity-relation-constraint paradigm to comprehensively represent all components of plane geometry, along with generative actions defined within this symbolic space. We then design a symbolic-visual-text pipeline that synthesizes symbolic sequences, maps them to corresponding visual and textual representations, and generates diverse question-answer (Q&A) pairs using large language models (LLMs). To the best of our knowledge, we are the first to propose a neuro-symbolic approach in generating multimodal reasoning data. Based on this framework, we construct NeSyGeo-CoT and NeSyGeo-Caption datasets, containing 100k samples, and release a new benchmark NeSyGeo-Test for evaluating geometric reasoning abilities in MLLMs. Experiments demonstrate that the proposal significantly and consistently improves the performance of multiple MLLMs under both reinforcement and supervised fine-tuning. With only 4k samples and two epochs of reinforcement fine-tuning, base models achieve improvements of up to +15.8% on MathVision, +8.4% on MathVerse, and +7.3% on GeoQA. Notably, a 4B model can be improved to outperform an 8B model from the same series on geometric reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.17121)