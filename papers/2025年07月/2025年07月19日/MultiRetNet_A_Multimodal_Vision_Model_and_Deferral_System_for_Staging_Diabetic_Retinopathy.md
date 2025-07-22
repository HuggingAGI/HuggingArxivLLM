# MultiRetNet：一个多模态视觉模型和转诊系统，用于分期糖尿病视网膜病变

发布时间：2025年07月19日

`其他

这篇论文主要探讨了糖尿病视网膜病变的检测和分期，结合了多模态数据和机器学习技术，但并未涉及大型语言模型的应用或理论，因此归类为其他。`

> MultiRetNet: A Multimodal Vision Model and Deferral System for Staging Diabetic Retinopathy

# 摘要

> 糖尿病视网膜病变（DR）是导致可预防性失明的主要原因之一，全球超过1亿人受到影响。在美国，低收入群体由于筛查资源有限，更可能在确诊前发展为晚期。共病情况进一步加速了疾病进展。我们提出MultiRetNet，这是一种结合视网膜成像、社会经济因素和共病概况的工作流程，旨在提升DR分期的准确性，并与临床延迟系统集成，实现临床人工回环的实施。我们实验了三种多模态融合方法，发现通过全连接层进行融合是最具通用性的方法。我们合成对抗性低质量图像，并利用对比学习训练延迟系统，引导模型识别需要临床医生审查的分布外样本。通过在次优图像上保持诊断准确性并整合关键健康数据，我们的系统能够提升早期检测率，尤其在资源匮乏的群体中，这些群体通常在DR晚期才被首次发现。这种方法可能降低医疗成本，提高早期检出率，并解决医疗资源获取的不平等问题，从而促进医疗公平性。

> Diabetic retinopathy (DR) is a leading cause of preventable blindness, affecting over 100 million people worldwide. In the United States, individuals from lower-income communities face a higher risk of progressing to advanced stages before diagnosis, largely due to limited access to screening. Comorbid conditions further accelerate disease progression. We propose MultiRetNet, a novel pipeline combining retinal imaging, socioeconomic factors, and comorbidity profiles to improve DR staging accuracy, integrated with a clinical deferral system for a clinical human-in-the-loop implementation. We experiment with three multimodal fusion methods and identify fusion through a fully connected layer as the most versatile methodology. We synthesize adversarial, low-quality images and use contrastive learning to train the deferral system, guiding the model to identify out-of-distribution samples that warrant clinician review. By maintaining diagnostic accuracy on suboptimal images and integrating critical health data, our system can improve early detection, particularly in underserved populations where advanced DR is often first identified. This approach may reduce healthcare costs, increase early detection rates, and address disparities in access to care, promoting healthcare equity.

[Arxiv](https://arxiv.org/abs/2507.14738)