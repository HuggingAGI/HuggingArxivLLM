# MagiC：评估多模态认知，迈向基于视觉的推理

发布时间：2025年07月09日

`其他` `视觉问答` `多模态推理`

> MagiC: Evaluating Multimodal Cognition Toward Grounded Visual Reasoning

# 摘要

> 大型视觉-语言模型的最新进展在视觉问答和多模态推理领域表现卓越。然而，这些模型是否真正具备基于视觉的推理能力，还是仅依赖于表面模式和数据偏见，仍有待验证。为此，我们推出了MagiC，一个全面的基准测试平台，专注于评估多模态认知能力。MagiC不仅关注答案的准确性，还深入考察推理过程的质量及其与视觉证据的一致性。

该基准测试包含两部分数据集：一部分是约5,500个由强模型生成的弱监督QA示例，另一部分是900个人工精审的示例，均附有详细标注，包括答案、推理过程和视觉定位信息。我们对15个视觉-语言模型进行了评估，参数规模从7B到70B不等，评估维度包括：最终答案的正确性、推理逻辑的有效性、视觉依据的准确性和自我纠错能力。

此外，MagiC还设置了诊断模块，用于测试模型在面对对抗性视觉线索时的鲁棒性，并评估其自我修正错误的能力。我们引入了全新的评估指标——MagiScore和StepSense，并通过全面分析，揭示了现有基于视觉推理方法的关键局限与潜在突破点。

> Recent advances in large vision-language models have led to impressive performance in visual question answering and multimodal reasoning. However, it remains unclear whether these models genuinely perform grounded visual reasoning or rely on superficial patterns and dataset biases. In this work, we introduce MagiC, a comprehensive benchmark designed to evaluate grounded multimodal cognition, assessing not only answer accuracy but also the quality of step-by-step reasoning and its alignment with relevant visual evidence. Our benchmark includes approximately 5,500 weakly supervised QA examples generated from strong model outputs and 900 human-curated examples with fine-grained annotations, including answers, rationales, and bounding box groundings. We evaluate 15 vision-language models ranging from 7B to 70B parameters across four dimensions: final answer correctness, reasoning validity, grounding fidelity, and self-correction ability. MagiC further includes diagnostic settings to probe model robustness under adversarial visual cues and assess their capacity for introspective error correction. We introduce new metrics such as MagiScore and StepSense, and provide comprehensive analyses that reveal key limitations and opportunities in current approaches to grounded visual reasoning.

[Arxiv](https://arxiv.org/abs/2507.07297)