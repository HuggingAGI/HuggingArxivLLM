# 利用大型语言模型理解驾驶风险：迈向老年驾驶员评估

发布时间：2025年07月11日

`LLM应用` `交通安全` `自动驾驶`

> Understanding Driving Risks using Large Language Models: Toward Elderly Driver Assessment

# 摘要

> 本研究探讨了多模态大型语言模型（LLM）——以ChatGPT-4o为例——在利用静态行车记录仪图像进行类人交通场景解读方面的潜力。我们重点关注了与老年驾驶员评估相关的三个关键任务：评估交通密度、判断路口能见度以及识别停车标志。这些任务需要复杂的场景理解，而不仅仅是简单的物体识别。通过采用零样本、少样本和多样本提示策略，我们以人工标注数据为参考标准，全面评估了模型的性能表现。评估指标包括精确率、召回率和F1分数。研究结果表明，提示设计对模型性能有着显著影响。具体而言，路口能见度的召回率从零样本条件下的21.7%提升到了多样本条件下的57.0%。在交通密度评估方面，模型与人工标注的一致性从53.5%提升至67.6%。而对于停车标志检测任务，模型表现出了较高的精确率（最高达86.3%），但召回率相对较低（约76.7%），这表明模型在预测时倾向于采取保守策略。输出稳定性分析发现，无论是人类还是模型，在解读结构模糊的场景时都存在一定困难。然而，模型生成的解释性文本与其预测结果保持一致，这有助于提高模型的可解释性。这些研究发现表明，通过精心设计的提示策略，LLMs有望成为场景级驾驶风险评估的有力辅助工具。未来的研究方向应包括利用更大规模的数据集、更多样化的标注者以及新一代模型架构，以进一步提升其在老年驾驶员评估中的应用效果。

> This study investigates the potential of a multimodal large language model (LLM), specifically ChatGPT-4o, to perform human-like interpretations of traffic scenes using static dashcam images. Herein, we focus on three judgment tasks relevant to elderly driver assessments: evaluating traffic density, assessing intersection visibility, and recognizing stop signs recognition. These tasks require contextual reasoning rather than simple object detection. Using zero-shot, few-shot, and multi-shot prompting strategies, we evaluated the performance of the model with human annotations serving as the reference standard. Evaluation metrics included precision, recall, and F1-score. Results indicate that prompt design considerably affects performance, with recall for intersection visibility increasing from 21.7% (zero-shot) to 57.0% (multi-shot). For traffic density, agreement increased from 53.5% to 67.6%. In stop-sign detection, the model demonstrated high precision (up to 86.3%) but a lower recall (approximately 76.7%), indicating a conservative response tendency. Output stability analysis revealed that humans and the model faced difficulties interpreting structurally ambiguous scenes. However, the model's explanatory texts corresponded with its predictions, enhancing interpretability. These findings suggest that, with well-designed prompts, LLMs hold promise as supportive tools for scene-level driving risk assessments. Future studies should explore scalability using larger datasets, diverse annotators, and next-generation model architectures for elderly driver assessments.

[Arxiv](https://arxiv.org/abs/2507.08367)