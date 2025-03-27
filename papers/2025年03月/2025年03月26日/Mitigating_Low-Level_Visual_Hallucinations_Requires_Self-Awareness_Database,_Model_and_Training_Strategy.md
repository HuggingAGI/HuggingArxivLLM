# 解决低级视觉幻觉需具备自我意识：数据库、模型与训练策略

发布时间：2025年03月26日

`LLM理论

理由：这篇论文主要探讨了多模态大语言模型中的幻觉问题，并提出了解决这一问题的理论方法，包括新模型和框架的开发，属于理论研究的范畴。` `计算机视觉` `图像处理`

> Mitigating Low-Level Visual Hallucinations Requires Self-Awareness: Database, Model and Training Strategy

# 摘要

> 多模态大语言模型的快速发展显著推动了视觉感知与理解的进步，将多种任务整合到单一的视觉问答框架中。然而，这些模型容易产生幻觉，这限制了它们作为人工智能系统的可靠性。尽管幻觉问题在自然语言处理和图像描述生成中已得到广泛研究，但对于低级视觉感知与理解（HLPU），尤其是图像质量评估任务中的幻觉现象，研究仍然不足。我们认为，这些幻觉源于模型内部缺乏清晰的自我认知。为了解决这一问题，我们首先介绍了HLPU指令数据库，这是首个专门针对低级视觉任务幻觉现象的指令数据库。该数据库包含约20万组问答对，并分为四个子集，涵盖不同类型的指令。随后，我们提出了自我认知失效消除（SAFEQA）模型，该模型通过利用图像特征、显著区域特征和质量特征来提升模型在低级视觉任务中的感知与理解能力。此外，我们提出了增强自我认知偏好优化（ESA-PO）框架，以提升模型对知识边界的认识，从而减少幻觉的发生。最后，我们在低级视觉任务上进行了全面的实验，结果表明，我们的方法显著提升了模型在这些任务中的自我认知能力，并减少了幻觉现象。值得注意的是，我们的方法不仅提高了模型的准确性和自我认知，还在多种评估指标上优于闭源模型。

> The rapid development of multimodal large language models has resulted in remarkable advancements in visual perception and understanding, consolidating several tasks into a single visual question-answering framework. However, these models are prone to hallucinations, which limit their reliability as artificial intelligence systems. While this issue is extensively researched in natural language processing and image captioning, there remains a lack of investigation of hallucinations in Low-level Visual Perception and Understanding (HLPU), especially in the context of image quality assessment tasks. We consider that these hallucinations arise from an absence of clear self-awareness within the models. To address this issue, we first introduce the HLPU instruction database, the first instruction database specifically focused on hallucinations in low-level vision tasks. This database contains approximately 200K question-answer pairs and comprises four subsets, each covering different types of instructions. Subsequently, we propose the Self-Awareness Failure Elimination (SAFEQA) model, which utilizes image features, salient region features and quality features to improve the perception and comprehension abilities of the model in low-level vision tasks. Furthermore, we propose the Enhancing Self-Awareness Preference Optimization (ESA-PO) framework to increase the model's awareness of knowledge boundaries, thereby mitigating the incidence of hallucination. Finally, we conduct comprehensive experiments on low-level vision tasks, with the results demonstrating that our proposed method significantly enhances self-awareness of the model in these tasks and reduces hallucinations. Notably, our proposed method improves both accuracy and self-awareness of the proposed model and outperforms close-source models in terms of various evaluation metrics.

[Arxiv](https://arxiv.org/abs/2503.20673)