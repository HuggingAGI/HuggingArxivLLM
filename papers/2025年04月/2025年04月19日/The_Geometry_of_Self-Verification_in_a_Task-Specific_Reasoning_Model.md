# 任务特定推理模型中的自我验证几何分析

发布时间：2025年04月19日

`LLM理论` `人工智能`

> The Geometry of Self-Verification in a Task-Specific Reasoning Model

# 摘要

> 推理模型如何验证自己的答案？我们通过使用DeepSeek R1的配方在CountDown任务上训练模型，深入研究这一问题。通过偏好调优导致模式坍缩的特性，我们成功训练出一个始终生成高度结构化且易于解析的思维链序列的模型。随后，我们从上至下和从下至上进行分析，揭示了模型验证输出的内在机制。从上至下的分析发现，门控线性单元（GLU）权重编码了“成功”或“错误”等与验证相关的标记，这些标记会根据模型推理步骤的正确性而激活。从下至上的分析则表明，“前一个标记头”在模型验证中扮演了关键角色。进一步研究发现，只需三个注意力头即可禁用模型验证，这揭示了验证机制中不可或缺的核心组件，为理解潜在更大验证回路提供了重要线索。

> How do reasoning models verify their own answers? We study this question by training a model using DeepSeek R1's recipe on the CountDown task. We leverage the fact that preference tuning leads to mode collapse, resulting in a model that always produces highly structured and easily parse-able chain-of-thought sequences. With this setup, we do a top-down and bottom-up analysis to reverse-engineer how the model verifies its outputs. Our top-down analysis reveals Gated Linear Unit (GLU) weights encoding verification-related tokens, such as ``success'' or ``incorrect'', which activate according to the correctness of the model's reasoning steps. Our bottom-up analysis reveals that ``previous-token heads'' are mainly responsible for model verification. Our analyses meet in the middle: drawing inspiration from inter-layer communication channels, we use the identified GLU vectors to localize as few as three attention heads that can disable model verification, pointing to a necessary component of a potentially larger verification circuit.

[Arxiv](https://arxiv.org/abs/2504.14379)