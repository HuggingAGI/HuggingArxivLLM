# DriveLMM-o1: 驾驶场景理解的逐步推理数据集与大型多模态模型

发布时间：2025年03月13日

`其他` `自动驾驶` `智能驾驶`

> DriveLMM-o1: A Step-by-Step Reasoning Dataset and Large Multimodal Model for Driving Scenario Understanding

# 摘要

> 大型多模态模型（LMMs）在视觉问答（VQA）任务中表现优异，但在需要复杂多步推理的场景下仍面临挑战。其中，自动驾驶任务尤为突出，它要求在决策前完成全面的认知处理。在这一领域，对视觉线索的序列化和解释性理解是实现有效感知、预测和规划的关键。然而，现有VQA基准测试多关注最终答案的准确性，而忽视了推理过程的重要性。同时，现有方法缺乏针对现实驾驶场景中逐步推理能力的全面评估框架。为解决这一问题，我们提出了DriveLMM-o1，一个专为推进自动驾驶逐步视觉推理设计的新数据集和基准测试。我们的基准测试包含18,000多个VQA训练样本和4,000多个测试样本，涵盖感知、预测和规划等多样化问题，每个问题均配有逐步推理过程，以确保自动驾驶场景中的逻辑推理。我们还开发了一个经过推理数据集微调的大型多模态模型，在复杂驾驶场景中展现出强大性能。此外，我们对开源和闭源方法在我们的新数据集上进行了全面基准测试，系统比较了它们在自动驾驶任务中的推理能力。与前最好的开源模型相比，我们的模型在最终答案准确性上提升了7.49%，推理得分提升了3.62%。我们的框架、数据集和模型可在https://github.com/ayesha-ishaq/DriveLMM-o1获取。

> While large multimodal models (LMMs) have demonstrated strong performance across various Visual Question Answering (VQA) tasks, certain challenges require complex multi-step reasoning to reach accurate answers. One particularly challenging task is autonomous driving, which demands thorough cognitive processing before decisions can be made. In this domain, a sequential and interpretive understanding of visual cues is essential for effective perception, prediction, and planning. Nevertheless, common VQA benchmarks often focus on the accuracy of the final answer while overlooking the reasoning process that enables the generation of accurate responses. Moreover, existing methods lack a comprehensive framework for evaluating step-by-step reasoning in realistic driving scenarios. To address this gap, we propose DriveLMM-o1, a new dataset and benchmark specifically designed to advance step-wise visual reasoning for autonomous driving. Our benchmark features over 18k VQA examples in the training set and more than 4k in the test set, covering diverse questions on perception, prediction, and planning, each enriched with step-by-step reasoning to ensure logical inference in autonomous driving scenarios. We further introduce a large multimodal model that is fine-tuned on our reasoning dataset, demonstrating robust performance in complex driving scenarios. In addition, we benchmark various open-source and closed-source methods on our proposed dataset, systematically comparing their reasoning capabilities for autonomous driving tasks. Our model achieves a +7.49% gain in final answer accuracy, along with a 3.62% improvement in reasoning score over the previous best open-source model. Our framework, dataset, and model are available at https://github.com/ayesha-ishaq/DriveLMM-o1.

[Arxiv](https://arxiv.org/abs/2503.10621)