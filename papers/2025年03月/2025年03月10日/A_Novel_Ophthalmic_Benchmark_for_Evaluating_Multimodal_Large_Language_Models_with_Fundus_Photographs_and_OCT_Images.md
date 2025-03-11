# 评估多模态大型语言模型的新型眼科基准——结合眼底照片与OCT图像。

发布时间：2025年03月10日

`LLM应用`

> A Novel Ophthalmic Benchmark for Evaluating Multimodal Large Language Models with Fundus Photographs and OCT Images

# 摘要

> 近年来，大型语言模型（LLMs）在医学领域展现了巨大潜力。在此基础上，多模态大型语言模型（MLLMs）将LLMs与视觉模型结合，能够处理临床数据和医学图像等多样化输入。在眼科领域，LLMs已被用于分析光学相干断层扫描（OCT）报告、辅助疾病分类，甚至预测治疗效果。然而，现有的MLLM基准测试往往未能捕捉真实临床实践中的复杂性，尤其是在OCT图像分析方面。许多现有研究存在样本量小、缺乏多样化OCT数据集以及专家验证不足等问题，这限制了我们对MLLMs解读OCT扫描能力的准确评估，也限制了其在眼科领域的广泛应用。我们通过严格的质量控制和专家标注，构建了一个包含439张眼底图像和75张OCT图像的数据集。采用标准化的API框架，我们评估了七种主流MLLM，发现它们在不同疾病上的诊断准确率存在显著差异。虽然某些模型在诊断糖尿病视网膜病变和年龄相关性黄斑变性等疾病时表现良好，但它们在处理脉络膜新生血管和近视等疾病时则显得力不从心，这凸显了现有模型性能的不一致性以及进一步优化的必要性。我们的研究结果强调了开发与临床实践紧密结合的基准测试的重要性，这有助于更准确地评估多模态大型语言模型（MLLMs）的能力。通过不断优化这些模型并拓展其应用范围，我们有望进一步提升其在眼科诊断和治疗中的潜力。

> In recent years, large language models (LLMs) have demonstrated remarkable potential across various medical applications. Building on this foundation, multimodal large language models (MLLMs) integrate LLMs with visual models to process diverse inputs, including clinical data and medical images. In ophthalmology, LLMs have been explored for analyzing optical coherence tomography (OCT) reports, assisting in disease classification, and even predicting treatment outcomes. However, existing MLLM benchmarks often fail to capture the complexities of real-world clinical practice, particularly in the analysis of OCT images. Many suffer from limitations such as small sample sizes, a lack of diverse OCT datasets, and insufficient expert validation. These shortcomings hinder the accurate assessment of MLLMs' ability to interpret OCT scans and their broader applicability in ophthalmology. Our dataset, curated through rigorous quality control and expert annotation, consists of 439 fundus images and 75 OCT images. Using a standardized API-based framework, we assessed seven mainstream MLLMs and observed significant variability in diagnostic accuracy across different diseases. While some models performed well in diagnosing conditions such as diabetic retinopathy and age-related macular degeneration, they struggled with others, including choroidal neovascularization and myopia, highlighting inconsistencies in performance and the need for further refinement. Our findings emphasize the importance of developing clinically relevant benchmarks to provide a more accurate assessment of MLLMs' capabilities. By refining these models and expanding their scope, we can enhance their potential to transform ophthalmic diagnosis and treatment.

[Arxiv](https://arxiv.org/abs/2503.07094)