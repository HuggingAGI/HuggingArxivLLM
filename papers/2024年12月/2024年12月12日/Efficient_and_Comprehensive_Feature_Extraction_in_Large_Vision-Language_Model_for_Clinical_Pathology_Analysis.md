# 大型视觉语言模型在临床病理学分析中的高效且全面的特征提取

发布时间：2024年12月12日

`LLM应用` `病理学`

> Efficient and Comprehensive Feature Extraction in Large Vision-Language Model for Clinical Pathology Analysis

# 摘要

> 病理诊断对确定疾病特征、指导治疗和评估预后意义重大，这高度依赖于对高分辨率全切片图像（WSI）的详尽、多尺度分析。然而，传统纯视觉模型存在特征提取冗余的问题，现有的大型视觉语言模型（LVLMs）又受输入分辨率限制，阻碍了其效率和准确性。为解决这些难题，我们提出了两项创新策略：混合任务引导的特征增强，引导针对跨尺度病变相关细节的特征提取；提示引导的细节特征完成，基于特定提示从WSI中整合粗细粒度特征，且不影响推理速度。借助涵盖癌症检测、分级、血管和神经侵犯识别等各类病理任务的490,000个样本的综合数据集，我们训练了病理学专用的LVLM——OmniPath。大量实验表明，该模型在诊断准确性和效率上显著优于现有方法，为众多病理应用中的辅助诊断提供了一种交互式、符合临床需求的途径。

> Pathological diagnosis is vital for determining disease characteristics, guiding treatment, and assessing prognosis, relying heavily on detailed, multi-scale analysis of high-resolution whole slide images (WSI). However, traditional pure vision models face challenges of redundant feature extraction, whereas existing large vision-language models (LVLMs) are limited by input resolution constraints, hindering their efficiency and accuracy. To overcome these issues, we propose two innovative strategies: the mixed task-guided feature enhancement, which directs feature extraction toward lesion-related details across scales, and the prompt-guided detail feature completion, which integrates coarse- and fine-grained features from WSI based on specific prompts without compromising inference speed. Leveraging a comprehensive dataset of 490,000 samples from diverse pathology tasks-including cancer detection, grading, vascular and neural invasion identification, and so on-we trained the pathology-specialized LVLM, OmniPath. Extensive experiments demonstrate that this model significantly outperforms existing methods in diagnostic accuracy and efficiency, offering an interactive, clinically aligned approach for auxiliary diagnosis in a wide range of pathology applications.

[Arxiv](https://arxiv.org/abs/2412.09521)