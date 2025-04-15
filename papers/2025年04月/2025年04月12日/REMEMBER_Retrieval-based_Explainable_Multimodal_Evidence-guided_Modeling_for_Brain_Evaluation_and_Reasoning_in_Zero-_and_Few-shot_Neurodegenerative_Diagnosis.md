# # REMEMBER: 基于检索的可解释多模态证据引导建模，用于零样本与少样本神经退行性诊断中的脑评估与推理

发布时间：2025年04月12日

`LLM应用` `医学影像`

> REMEMBER: Retrieval-based Explainable Multimodal Evidence-guided Modeling for Brain Evaluation and Reasoning in Zero- and Few-shot Neurodegenerative Diagnosis

# 摘要

> 及时准确诊断神经退行性疾病（如阿尔茨海默病）对疾病管理至关重要。然而，现有深度学习模型依赖大规模标注数据集，且常被视为“黑箱”。临床实践中，数据集常规模较小或未标注，限制了深度学习方法的潜力。为此，我们推出 REMEMBER——一种基于检索的可解释多模态证据引导建模框架，用于大脑评估和推理。REMEMBER 利用脑部 MRI 扫描，通过基于参考的推理过程实现零样本和少量样本的阿尔茨海默病诊断。具体而言，REMEMBER 首先使用专家标注的参考数据训练对比对齐的视觉-文本模型，并扩展伪文本模态，编码异常类型、诊断标签和综合临床描述。在推理阶段，REMEMBER 从整理好的数据集中检索相似且经人工验证的案例，并通过专用的证据编码模块和基于注意力的推理头整合其上下文信息。这种基于证据的设计使 REMEMBER 能够通过将预测基于检索到的图像和文本上下文来模拟现实世界中的临床决策过程。具体而言，REMEMBER 输出诊断预测结果，同时生成可解释的报告，其中包括参考图像和与临床工作流程一致的解释。实验结果表明，REMEMBER 在零样本和少量样本情况下表现出稳健性能，为基于神经影像的实际诊断提供了一个强大且可解释的框架，尤其是在数据有限的情况下。

> Timely and accurate diagnosis of neurodegenerative disorders, such as Alzheimer's disease, is central to disease management. Existing deep learning models require large-scale annotated datasets and often function as "black boxes". Additionally, datasets in clinical practice are frequently small or unlabeled, restricting the full potential of deep learning methods. Here, we introduce REMEMBER -- Retrieval-based Explainable Multimodal Evidence-guided Modeling for Brain Evaluation and Reasoning -- a new machine learning framework that facilitates zero- and few-shot Alzheimer's diagnosis using brain MRI scans through a reference-based reasoning process. Specifically, REMEMBER first trains a contrastively aligned vision-text model using expert-annotated reference data and extends pseudo-text modalities that encode abnormality types, diagnosis labels, and composite clinical descriptions. Then, at inference time, REMEMBER retrieves similar, human-validated cases from a curated dataset and integrates their contextual information through a dedicated evidence encoding module and attention-based inference head. Such an evidence-guided design enables REMEMBER to imitate real-world clinical decision-making process by grounding predictions in retrieved imaging and textual context. Specifically, REMEMBER outputs diagnostic predictions alongside an interpretable report, including reference images and explanations aligned with clinical workflows. Experimental results demonstrate that REMEMBER achieves robust zero- and few-shot performance and offers a powerful and explainable framework to neuroimaging-based diagnosis in the real world, especially under limited data.

[Arxiv](https://arxiv.org/abs/2504.09354)