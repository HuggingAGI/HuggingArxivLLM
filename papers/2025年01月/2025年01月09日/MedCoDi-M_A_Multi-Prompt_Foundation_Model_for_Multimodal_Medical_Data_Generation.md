# MedCoDi-M: 多模态医学数据生成的多提示基础模型

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了一个名为MedCoDi-M的模型，该模型专为多模态医疗数据生成设计，并利用对比学习和海量数据构建共享潜在空间。虽然论文中提到了潜在扩散模型和多模态数据的整合，但核心内容仍然是关于如何利用大型模型（67.7亿参数）来解决医疗领域中的数据生成问题。因此，这篇论文属于LLM应用类别，因为它涉及到了大型模型在特定领域（医疗）中的应用。` `数据生成`

> MedCoDi-M: A Multi-Prompt Foundation Model for Multimodal Medical Data Generation

# 摘要

> # 摘要
人工智能正在革新医疗实践，提升诊断精度和医疗服务。然而，其在医疗场景中的应用仍面临数据可用性和隐私限制等重大挑战。合成数据作为一种有前景的解决方案，既能缓解数据稀缺问题，又能保护隐私。最近，潜在扩散模型成为生成高质量合成数据的强大工具。同时，多模态数据的整合备受关注，凸显了对能够处理多模态医疗数据模型的需求。现有方法难以整合互补信息，且无法同时生成多种模态。为此，我们推出了MedCoDi-M，一个拥有67.7亿参数的模型，专为多模态医疗数据生成设计。该模型遵循基础模型范式，利用对比学习和海量数据构建共享潜在空间，捕捉不同数据模态间的关系。此外，我们引入了多提示训练技术，显著提升了MedCoDi-M在不同场景下的生成能力。我们对MedCoDi-M进行了全面验证：首先，在MIMIC-CXR数据集上，我们将其与五个竞争对手进行了基准测试，该数据集是胸部X光和放射学报告生成领域的顶尖数据集。其次，我们与专业放射科医生进行了视觉图灵测试，评估生成数据的真实性和临床相关性，确保其与现实场景一致。最后，我们评估了MedCoDi-M在解决医疗领域关键挑战（如匿名化、数据稀缺和不平衡学习）中的实用性。结果令人鼓舞，证明了MedCoDi-M在医疗环境中的广泛应用潜力。项目页面位于https://cosbidev.github.io/MedCoDi-M/。

> Artificial Intelligence is revolutionizing medical practice, enhancing diagnostic accuracy and healthcare delivery. However, its adaptation in medical settings still faces significant challenges, related to data availability and privacy constraints. Synthetic data has emerged as a promising solution to mitigate these issues, addressing data scarcity while preserving privacy. Recently, Latent Diffusion Models have emerged as a powerful tool for generating high-quality synthetic data. Meanwhile, the integration of different modalities has gained interest, emphasizing the need of models capable of handle multimodal medical data. Existing approaches struggle to integrate complementary information and lack the ability to generate modalities simultaneously. To address this challenge, we present MedCoDi-M, a 6.77-billion-parameter model, designed for multimodal medical data generation, that, following Foundation Model paradigm, exploits contrastive learning and large quantity of data to build a shared latent space which capture the relationships between different data modalities. Further, we introduce the Multi-Prompt training technique, which significantly boosts MedCoDi-M's generation under different settings. We extensively validate MedCoDi-M: first we benchmark it against five competitors on the MIMIC-CXR dataset, a state-of-the-art dataset for Chest X-ray and radiological report generation. Secondly, we perform a Visual Turing Test with expert radiologists to assess the realism and clinical relevance of the generated data, ensuring alignment with real-world scenarios. Finally, we assess the utility of MedCoDi-M in addressing key challenges in the medical field, such as anonymization, data scarcity and imbalance learning. The results are promising, demonstrating the applicability of MedCoDi-M in medical contexts. Project page is at https://cosbidev.github.io/MedCoDi-M/.

[Arxiv](https://arxiv.org/abs/2501.04614)