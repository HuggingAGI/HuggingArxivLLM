# # OpenNav：基于多模态大语言模型的开放世界导航

发布时间：2025年07月23日

`LLM应用` `机器人导航` `自动驾驶`

> OpenNav: Open-World Navigation with Multimodal Large Language Models

# 摘要

> 预训练大型语言模型（LLMs）凭借强大的常识推理能力，为机器人导航和规划任务开辟了新的可能。然而，如何在开放世界中将语言指令转化为实际机器人动作，仍是一个待解决的难题，尤其是在无需依赖预定义动作的情况下。本研究致力于让机器人能够理解并分解复杂指令，最终通过一系列轨迹点完成多样化的导航任务，无论面对何种开放集指令和对象。我们发现，多模态大型语言模型（MLLMs）在处理自由形式语言指令时展现出卓越的跨模态理解能力，能够精准把握场景。更关键的是，MLLMs凭借其代码生成能力，可与视觉-语言感知模型协同工作，生成组合式2D鸟瞰图价值图，将语义知识与空间信息有机结合，从而提升机器人对空间的理解。为验证这一方法，我们借助大规模自动驾驶数据集（AVDs），在户外导航任务中成功验证了零样本视觉-语言导航框架，证明其不仅能够准确执行多样化自然语言指令，还能有效应对物体检测误差和语言模糊性。此外，我们在Husky机器人上完成了室内和室外场景的测试，充分验证了该框架在现实环境中的可靠性和实用性。更多细节请访问https://trailab.github.io/OpenNav-website/。

> Pre-trained large language models (LLMs) have demonstrated strong common-sense reasoning abilities, making them promising for robotic navigation and planning tasks. However, despite recent progress, bridging the gap between language descriptions and actual robot actions in the open-world, beyond merely invoking limited predefined motion primitives, remains an open challenge. In this work, we aim to enable robots to interpret and decompose complex language instructions, ultimately synthesizing a sequence of trajectory points to complete diverse navigation tasks given open-set instructions and open-set objects. We observe that multi-modal large language models (MLLMs) exhibit strong cross-modal understanding when processing free-form language instructions, demonstrating robust scene comprehension. More importantly, leveraging their code-generation capability, MLLMs can interact with vision-language perception models to generate compositional 2D bird-eye-view value maps, effectively integrating semantic knowledge from MLLMs with spatial information from maps to reinforce the robot's spatial understanding. To further validate our approach, we effectively leverage large-scale autonomous vehicle datasets (AVDs) to validate our proposed zero-shot vision-language navigation framework in outdoor navigation tasks, demonstrating its capability to execute a diverse range of free-form natural language navigation instructions while maintaining robustness against object detection errors and linguistic ambiguities. Furthermore, we validate our system on a Husky robot in both indoor and outdoor scenes, demonstrating its real-world robustness and applicability. Supplementary videos are available at https://trailab.github.io/OpenNav-website/

[Arxiv](https://arxiv.org/abs/2507.18033)