# 多模态人机协同实现医学影像质量控制：融合自适应数据整理与闭环评估的混合智能框架

发布时间：2025年03月10日

`LLM应用` `医学影像` `人工智能`

> Multimodal Human-AI Synergy for Medical Imaging Quality Control: A Hybrid Intelligence Framework with Adaptive Dataset Curation and Closed-Loop Evaluation

# 摘要

> # 摘要  
医学影像质量控制（QC）对于准确诊断至关重要，然而传统QC方法仍然 labor-intensive and subjective。为了解决这一挑战，本研究建立了一个标准化的医学影像QC数据集和评估框架，系统性地评估了大型语言模型（LLMs）在图像质量评估和报告标准化方面的表现。具体来说，我们首先构建并匿名化了一个包含161份胸部X光片（CXR）和219份CT报告的数据集用于评估。然后，我们基于召回率、精确率和F1分数对多个LLMs进行了评估，包括Gemini 2.0-Flash、GPT-4o和DeepSeek-R1，以检测技术错误和不一致。实验结果表明，Gemini 2.0-Flash在CXR任务中实现了90的Macro F1分数，展现了良好的泛化能力，但在细节处理上仍有提升空间。DeepSeek-R1在CT报告审核中表现突出，召回率达到62.23%，优于其他模型。然而，其蒸馏版本表现不佳，而InternLM2.5-7B-chat展现了最高的额外发现率，表明其具有更广泛的错误检测能力，但精确度较低。这些发现凸显了LLMs在医学影像QC中的潜力，其中DeepSeek-R1和Gemini 2.0-Flash表现尤为出色。


> Medical imaging quality control (QC) is essential for accurate diagnosis, yet traditional QC methods remain labor-intensive and subjective. To address this challenge, in this study, we establish a standardized dataset and evaluation framework for medical imaging QC, systematically assessing large language models (LLMs) in image quality assessment and report standardization. Specifically, we first constructed and anonymized a dataset of 161 chest X-ray (CXR) radiographs and 219 CT reports for evaluation. Then, multiple LLMs, including Gemini 2.0-Flash, GPT-4o, and DeepSeek-R1, were evaluated based on recall, precision, and F1 score to detect technical errors and inconsistencies. Experimental results show that Gemini 2.0-Flash achieved a Macro F1 score of 90 in CXR tasks, demonstrating strong generalization but limited fine-grained performance. DeepSeek-R1 excelled in CT report auditing with a 62.23\% recall rate, outperforming other models. However, its distilled variants performed poorly, while InternLM2.5-7B-chat exhibited the highest additional discovery rate, indicating broader but less precise error detection. These findings highlight the potential of LLMs in medical imaging QC, with DeepSeek-R1 and Gemini 2.0-Flash demonstrating superior performance.

[Arxiv](https://arxiv.org/abs/2503.07032)