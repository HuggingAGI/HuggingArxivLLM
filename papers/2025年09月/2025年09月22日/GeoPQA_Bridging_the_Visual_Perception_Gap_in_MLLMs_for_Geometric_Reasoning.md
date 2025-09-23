# GeoPQA：弥合多模态大型语言模型（MLLMs）几何推理中的视觉感知鸿沟

发布时间：2025年09月22日

`强化学习` `基础理论`

> GeoPQA: Bridging the Visual Perception Gap in MLLMs for Geometric Reasoning

# 摘要

> 强化学习（RL）的最新进展显著提升了大型语言模型（LLMs）的推理能力，然而对多模态大型语言模型（MLLMs）的作用却十分有限。尤其在几何推理这类视觉密集型任务中，MLLMs频繁出现“幻觉”现象，进而造成推理结果失准。我们认为这一问题源于MLLMs存在的感知瓶颈，它制约了推理训练的实际收益。为量化这一感知瓶颈，我们构建了几何感知问答（GeoPQA）基准数据集，专门用于评估基本几何概念和空间关系的理解能力。在GeoPQA上的实验结果表明，MLLMs在视觉感知方面存在明显短板，这直接限制了强化学习奖励信号对模型的有效训练。为突破这一瓶颈，我们提出两阶段强化学习训练框架：先提升几何结构的视觉感知能力，再培养模型的推理能力。将该框架应用于Qwen2.5-VL-3B-Instruct模型后，与直接进行推理训练的方法相比，两阶段训练使几何推理能力提升9.7%，几何问题解决能力提升9.1%。该方法还能泛化到图形理解等其他视觉密集领域，凸显了感知基础对MLLM实现有效推理的关键作用。

> Recent advancements in reinforcement learning (RL) have enhanced the reasoning abilities of large language models (LLMs), yet the impact on multimodal LLMs (MLLMs) is limited. Particularly in vision-intensive tasks like geometric reasoning, MLLMs hallucinate frequently, leading to inaccurate reasoning. We attribute this to the perceptual bottleneck in MLLMs, which caps the benefits of reasoning training. To quantify this, we design a Geo-Perception Question-Answering (GeoPQA) benchmark, targeting basic geometric concepts and spatial relationships. Experiments on GeoPQA reveal significant shortcomings of MLLMs in visual perception, which constrain RL reward signals for effective training. To address this bottleneck, we propose a two-stage RL training framework by first enhancing the visual perception of geometric structures, then fostering reasoning capabilities. Applied to Qwen2.5-VL-3B-Instruct, our two-stage training improves geometric reasoning by 9.7% and geometric problem solving by 9.1%, compared to the direct reasoning training approach. Our method also generalizes to other vision-intensive domains like figure understanding, highlighting the importance of perceptual grounding in effective MLLM reasoning.

[Arxiv](https://arxiv.org/abs/2509.17437)