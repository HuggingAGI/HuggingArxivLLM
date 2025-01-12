# Ultrasound-QBench: LLMs 能否助力超声成像质量评估？

发布时间：2025年01月05日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在超声图像质量评估任务中的应用，具体介绍了Ultrasound-QBench基准的构建和评估结果。论文的核心是探讨如何利用MLLMs来解决医学成像中的实际问题，属于LLM在实际场景中的应用研究。` `医学成像`

> Ultrasound-QBench: Can LLMs Aid in Quality Assessment of Ultrasound Imaging?

# 摘要

> 随着超声检查数量的激增，由于操作者水平和成像环境的差异，低质量超声图像逐渐增多，严重影响了诊断准确性，甚至在关键病例中可能导致重新诊断。为了帮助临床医生筛选高质量超声图像并确保诊断准确，我们推出了Ultrasound-QBench，这是一个综合基准，用于系统评估多模态大型语言模型（MLLMs）在超声图像质量评估任务中的表现。Ultrasound-QBench包含两个数据集：IVUSQA（7,709张图像）和CardiacUltraQA（3,863张图像），这些图像涵盖了常见超声伪影，并由专业超声专家标注为高、中、低三个质量等级。我们将质量评估任务分解为定性分类、定量评分和比较评估三个维度。通过对7个开源MLLMs和1个专有MLLMs的评估，发现MLLMs在超声图像质量分类的低级视觉任务中具备初步能力。我们希望这一基准能激励研究社区进一步挖掘和提升MLLMs在医学成像任务中的潜力。

> With the dramatic upsurge in the volume of ultrasound examinations, low-quality ultrasound imaging has gradually increased due to variations in operator proficiency and imaging circumstances, imposing a severe burden on diagnosis accuracy and even entailing the risk of restarting the diagnosis in critical cases. To assist clinicians in selecting high-quality ultrasound images and ensuring accurate diagnoses, we introduce Ultrasound-QBench, a comprehensive benchmark that systematically evaluates multimodal large language models (MLLMs) on quality assessment tasks of ultrasound images. Ultrasound-QBench establishes two datasets collected from diverse sources: IVUSQA, consisting of 7,709 images, and CardiacUltraQA, containing 3,863 images. These images encompassing common ultrasound imaging artifacts are annotated by professional ultrasound experts and classified into three quality levels: high, medium, and low. To better evaluate MLLMs, we decompose the quality assessment task into three dimensionalities: qualitative classification, quantitative scoring, and comparative assessment. The evaluation of 7 open-source MLLMs as well as 1 proprietary MLLMs demonstrates that MLLMs possess preliminary capabilities for low-level visual tasks in ultrasound image quality classification. We hope this benchmark will inspire the research community to delve deeper into uncovering and enhancing the untapped potential of MLLMs for medical imaging tasks.

[Arxiv](https://arxiv.org/abs/2501.02751)