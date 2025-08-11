# 基于文本嵌入的Swin-UMamba模型用于深部病变分割

发布时间：2025年08月08日

`LLM应用

摘要分析：该论文探讨了将大型语言模型（LLMs）应用于医学图像分割任务，具体是将文本信息与图像特征结合，以提高病变分割的准确性。这属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `医学影像` `计算机视觉`

> Text Embedded Swin-UMamba for DeepLesion Segmentation

# 摘要

> CT图像中的病变分割能够实现对慢性疾病的临床评估（例如淋巴瘤）的自动测量。将大型语言模型（LLMs）整合到病变分割流程中，有望将图像特征与放射科报告中的病变特征描述相结合。在本研究中，我们探讨了将文本信息融入Swin-UMamba架构用于病变分割任务的可行性。我们使用了公开的ULS23 DeepLesion数据集，并结合了报告中对病变发现的简要描述。在测试数据集上，病变分割的Dice得分为82%，Hausdorff距离为6.58（像素）。所提出的Text-Swin-UMamba模型优于先前的方法：与基于LLM的LanGuideMedSeg模型相比，Dice得分提高了37%（p < 0.001），并且分别比纯图像驱动的xLSTM-UNet和nnUNet模型高出1.74%和0.22%。该数据集和代码可在https://github.com/ruida/LLM-Swin-UMamba访问。

> Segmentation of lesions on CT enables automatic measurement for clinical assessment of chronic diseases (e.g., lymphoma). Integrating large language models (LLMs) into the lesion segmentation workflow offers the potential to combine imaging features with descriptions of lesion characteristics from the radiology reports. In this study, we investigate the feasibility of integrating text into the Swin-UMamba architecture for the task of lesion segmentation. The publicly available ULS23 DeepLesion dataset was used along with short-form descriptions of the findings from the reports. On the test dataset, a high Dice Score of 82% and low Hausdorff distance of 6.58 (pixels) was obtained for lesion segmentation. The proposed Text-Swin-UMamba model outperformed prior approaches: 37% improvement over the LLM-driven LanGuideMedSeg model (p < 0.001),and surpassed the purely image-based xLSTM-UNet and nnUNet models by 1.74% and 0.22%, respectively. The dataset and code can be accessed at https://github.com/ruida/LLM-Swin-UMamba

[Arxiv](https://arxiv.org/abs/2508.06453)