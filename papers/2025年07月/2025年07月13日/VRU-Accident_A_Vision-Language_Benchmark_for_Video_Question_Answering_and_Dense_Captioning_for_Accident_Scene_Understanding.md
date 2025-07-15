# # VRU-Accident: 一个用于视频问答和密集字幕的视觉-语言基准测试，旨在帮助更好地理解事故场景

发布时间：2025年07月13日

`LLM应用` `自动驾驶` `模型评估`

> VRU-Accident: A Vision-Language Benchmark for Video Question Answering and Dense Captioning for Accident Scene Understanding

# 摘要

> 保障弱势道路使用者（如行人和骑行者）的安全是自动驾驶系统面临的关键挑战之一，因为涉及这些群体的交通事故往往会造成严重甚至致命的后果。尽管多模态大型语言模型（MLLMs）在提升自动驾驶车辆的场景理解与决策能力方面展现出巨大潜力，但目前仍缺乏一个标准化的基准来定量评估这些模型在涉及弱势道路使用者的复杂、安全关键场景中的推理能力。为填补这一空白，我们提出了VRU-Accident——一个大规模的视觉-语言基准，专注于评估MLLMs在涉及弱势道路使用者的高风险交通场景中的表现。

VRU-Accident包含了1000个真实世界行车记录仪事故视频，并标注了6000个涵盖六个安全关键类别的多选题问答对（包含24000个候选选项和3400个唯一答案选项），以及1000个密集场景描述。与以往研究不同，我们的基准聚焦于VRU-车辆事故，提供丰富且细致的标注，能够全面捕捉事故的空间-时间动态和因果语义。

为了全面评估当前MLLMs的能力，我们在多选题VQA任务和密集描述任务上对17个最先进的模型进行了系统性评估。研究发现，尽管MLLMs在处理视觉基础属性方面表现尚可，但它们在推理和描述事故原因、类型以及可预防性方面仍面临重大挑战。

> Ensuring the safety of vulnerable road users (VRUs), such as pedestrians and cyclists, is a critical challenge for autonomous driving systems, as crashes involving VRUs often result in severe or fatal consequences. While multimodal large language models (MLLMs) have shown promise in enhancing scene understanding and decision making in autonomous vehicles, there is currently no standardized benchmark to quantitatively evaluate their reasoning abilities in complex, safety-critical scenarios involving VRUs. To address this gap, we present VRU-Accident, a large-scale vision-language benchmark designed to evaluate MLLMs in high-risk traffic scenarios involving VRUs. VRU-Accident comprises 1K real-world dashcam accident videos, annotated with 6K multiple-choice question-answer pairs across six safety-critical categories (with 24K candidate options and 3.4K unique answer choices), as well as 1K dense scene descriptions. Unlike prior works, our benchmark focuses explicitly on VRU-vehicle accidents, providing rich, fine-grained annotations that capture both spatial-temporal dynamics and causal semantics of accidents. To assess the current landscape of MLLMs, we conduct a comprehensive evaluation of 17 state-of-the-art models on the multiple-choice VQA task and on the dense captioning task. Our findings reveal that while MLLMs perform reasonably well on visually grounded attributes, they face significant challenges in reasoning and describing accident causes, types, and preventability.

[Arxiv](https://arxiv.org/abs/2507.09815)