# 通过视觉语言模型中发现的隐式推理路径，将视觉问答提升至新高度

发布时间：2025年03月18日

`LLM应用` `视觉问答` `多模态学习`

> Elevating Visual Question Answering through Implicitly Learned Reasoning Pathways in LVLMs

# 摘要

> 大型视觉-语言模型（LVLMs）在多模态任务中表现出色，但在需要多步推理的复杂视觉任务中仍显不足。为解决这一问题，我们提出MF-SQ-LLaVA，通过端到端训练实现隐式自我提问来增强模型能力。我们的方法通过在视觉问答数据集中添加由子问题和答案组成的推理链，并采用多任务损失函数训练模型，以促进中间步骤的生成与解答，同时预测最终答案。实验结果表明，MF-SQ-LLaVA在ScienceQA和VQAv2数据集上显著超越现有最先进模型的表现。消融实验验证了各组件的有效性，而人类评估则证明了我们的方法在推理准确性和连贯性上的显著提升。

> Large Vision-Language Models (LVLMs) have shown remarkable progress in various multimodal tasks, yet they often struggle with complex visual reasoning that requires multi-step inference. To address this limitation, we propose MF-SQ-LLaVA, a novel approach that enhances LVLMs by enabling implicit self-questioning through end-to-end training. Our method involves augmenting visual question answering datasets with reasoning chains consisting of sub-question and answer pairs, and training the LVLM with a multi-task loss that encourages the generation and answering of these intermediate steps, as well as the prediction of the final answer. We conduct extensive experiments on the ScienceQA and VQAv2 datasets, demonstrating that MF-SQ-LLaVA significantly outperforms existing state-of-the-art models, including the base LLaVA and the original SQ-LLaVA. Ablation studies further validate the contribution of each component of our approach, and human evaluation confirms the improved accuracy and coherence of the reasoning process enabled by our method.

[Arxiv](https://arxiv.org/abs/2503.14674)