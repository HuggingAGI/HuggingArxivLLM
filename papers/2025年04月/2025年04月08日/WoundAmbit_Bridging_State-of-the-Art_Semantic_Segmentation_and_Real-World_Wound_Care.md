# WoundAmbit：连接前沿语义分割与实际伤口护理

发布时间：2025年04月08日

`其他

理由：这篇论文主要探讨了慢性伤口的自动化监测，特别是通过移动设备拍摄图像来实现远程跟踪。虽然它涉及到AI模型，如语义分割模型，但并没有直接涉及大型语言模型（LLM）的应用或理论。因此，它更适合归类为“其他”。` `远程医疗`

> WoundAmbit: Bridging State-of-the-Art Semantic Segmentation and Real-World Wound Care

# 摘要

> 慢性伤口困扰着大量人群，特别是行动不便且伴有多种健康问题的老年人和糖尿病患者。通过移动设备拍摄图像实现的自动化伤口监测，可以通过远程跟踪伤口大小来减少面对面的医生访问。语义分割在此过程中至关重要，然而伤口分割在医学影像研究中仍处于探索阶段。为解决这一问题，我们对来自通用视觉、医学影像以及公开伤口挑战赛中的顶尖方法进行了基准测试。为了公平比较，我们统一了训练、数据增强和评估流程，并通过交叉验证来最小化数据划分偏差。我们还评估了实际部署的相关方面，包括对分布外伤口数据集的泛化能力、计算效率和可解释性。此外，我们提出了一种基于参考对象的方法，将AI生成的掩膜转换为具有临床意义的伤口大小估计，并根据医生评估对最佳模型的掩膜质量和尺寸估计进行了评估。总体而言，基于变压器的TransNeXt展现了最高的泛化能力。尽管推理时间存在差异，但所有模型在CPU上至少可以达到每秒处理一张图像，这对于预期应用而言是足够的。可解释性分析通常显示伤口区域的显著激活，突出了对临床相关特征的关注。专家评估显示所有分析模型的掩膜获得了高度认可，其中VWFormer和ConvNeXtS backbone表现最佳。尺寸检索准确性在各模型间相似，且预测结果与专家标注高度一致。最后，我们展示了如何将我们的AI驱动的伤口大小估计框架WoundAmbit整合到一个定制的远程医疗系统中。我们的代码将在发表后发布到GitHub。

> Chronic wounds affect a large population, particularly the elderly and diabetic patients, who often exhibit limited mobility and co-existing health conditions. Automated wound monitoring via mobile image capture can reduce in-person physician visits by enabling remote tracking of wound size. Semantic segmentation is key to this process, yet wound segmentation remains underrepresented in medical imaging research. To address this, we benchmark state-of-the-art deep learning models from general-purpose vision, medical imaging, and top methods from public wound challenges. For fair comparison, we standardize training, data augmentation, and evaluation, conducting cross-validationto minimize partitioning bias. We also assess real-world deployment aspects, including generalization to an out-of-distribution wound dataset, computational efficiency, and interpretability. Additionally, we propose a reference object-based approach to convert AI-generated masks into clinically relevant wound size estimates, and evaluate this, along with mask quality, for the best models based on physician assessments. Overall, the transformer-based TransNeXt showed the highest levels of generalizability. Despite variations in inference times, all models processed at least one image per second on the CPU, which is deemed adequate for the intended application. Interpretability analysis typically revealed prominent activations in wound regions, emphasizing focus on clinically relevant features. Expert evaluation showed high mask approval for all analyzed models, with VWFormer and ConvNeXtS backbone performing the best. Size retrieval accuracy was similar across models, and predictions closely matched expert annotations. Finally, we demonstrate how our AI-driven wound size estimation framework, WoundAmbit, can be integrated into a custom telehealth system. Our code will be made available on GitHub upon publication.

[Arxiv](https://arxiv.org/abs/2504.06185)