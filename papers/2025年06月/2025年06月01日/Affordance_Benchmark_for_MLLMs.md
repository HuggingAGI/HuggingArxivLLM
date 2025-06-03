# 多语言大模型能力评估基准

发布时间：2025年06月01日

`LLM应用` `人工智能` `人机交互`

> Affordance Benchmark for MLLMs

# 摘要

> 情境-动作理论指出，环境天然蕴含着行动的可能性，这些可能性塑造了我们的感知与行为。多模态大型语言模型（MLLMs）在视觉-语言任务中表现出色，但在感知情境-动作这一关键能力上仍有待深入研究，而这对于实现直观且安全的人机交互至关重要。为此，我们推出了A4Bench——首个专注于评估MLLMs情境-动作感知能力的基准测试。该基准测试从两个维度展开：1）构成性情境-动作，通过1,282个问题-答案对，涵盖九个子领域，考察模型对物体固有属性的理解深度；2）转变性情境-动作，利用718个更具挑战性的问题-答案对，深入挖掘动态变化和语境细微差别（如误导性、时间依赖性、文化差异或个体特异性的情境-动作）。我们对比了17个MLLMs（包括9个专有模型和8个开源模型）与人类的表现，发现专有模型普遍优于开源模型，但所有模型的能力均存在明显局限，尤其在转变性情境-动作感知方面表现不足。值得注意的是，即使是表现最佳的模型，如Gemini-2.0-Pro（整体精确匹配准确率为18.05%），与人类表现相比仍有显著差距（人类最佳准确率：85.34%，最差：81.25%）。这些发现不仅揭示了MLLMs在环境理解上的关键短板，更为开发更强大、更具语境感知能力的AI系统奠定了研究基础。A4Bench数据集现已开放，访问地址为：https://github.com/JunyingWang959/A4Bench/。

> Affordance theory posits that environments inherently offer action possibilities that shape perception and behavior. While Multimodal Large Language Models (MLLMs) excel in vision-language tasks, their ability to perceive affordance, which is crucial for intuitive and safe interactions, remains underexplored. To address this, we introduce A4Bench, a novel benchmark designed to evaluate the affordance perception abilities of MLLMs across two dimensions: 1) Constitutive Affordance}, assessing understanding of inherent object properties through 1,282 question-answer pairs spanning nine sub-disciplines, and 2) Transformative Affordance, probing dynamic and contextual nuances (e.g., misleading, time-dependent, cultural, or individual-specific affordance) with 718 challenging question-answer pairs. Evaluating 17 MLLMs (nine proprietary and eight open-source) against human performance, we find that proprietary models generally outperform open-source counterparts, but all exhibit limited capabilities, particularly in transformative affordance perception. Furthermore, even top-performing models, such as Gemini-2.0-Pro (18.05% overall exact match accuracy), significantly lag behind human performance (best: 85.34%, worst: 81.25%). These findings highlight critical gaps in environmental understanding of MLLMs and provide a foundation for advancing AI systems toward more robust, context-aware interactions. The dataset is available in https://github.com/JunyingWang959/A4Bench/.

[Arxiv](https://arxiv.org/abs/2506.00893)