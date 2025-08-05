# 组学数据的特征遮蔽建模在组织病理学与分子特征之间的多模态表示学习

发布时间：2025年08月01日

`LLM应用` `计算病理学` `多模态`

> Masked Omics Modeling for Multimodal Representation Learning across Histopathology and Molecular Profiles

# 摘要

> 自监督学习推动了计算病理学的革命性发展，使模型能够从苏木精和伊红（H&E）染色的癌症组织中学习丰富的表征。然而，仅凭组织病理学往往难以实现分子特征化和理解临床结果，因为关键信息通常隐藏在高维组学数据（如转录组学、甲基组学或基因组学）中。我们在此介绍MORPHEUS，一个基于统一变压器的预训练框架，能够将组织病理学和多组学数据融合到共享的潜在空间中。MORPHEUS的核心创新在于通过遮蔽建模目标对随机选择的组学部分进行处理，从而引导模型学习具有生物意义的跨模态关系。同一个预训练网络可灵活应用于组织病理学单独分析，或与任意组学模态组合使用，轻松适应不同输入。此外，MORPHEUS支持任意到任意的组学生成，能够从任意模态子集（包括仅H&E）推断出一种或多种组学谱。MORPHEUS在大规模泛癌队列上预训练后，在多种模态组合和任务中均超越现有最先进的方法，展现出作为肿瘤学多模态基础模型开发框架的巨大潜力。代码可在GitHub上获取：https://github.com/Lucas-rbnt/MORPHEUS

> Self-supervised learning has driven major advances in computational pathology by enabling models to learn rich representations from hematoxylin and eosin (H&E)-stained cancer tissue. However, histopathology alone often falls short for molecular characterization and understanding clinical outcomes, as important information is contained in high-dimensional omics profiles like transcriptomics, methylomics, or genomics. In this work, we introduce MORPHEUS, a unified transformer-based pre-training framework that encodes both histopathology and multi-omics data into a shared latent space. At its core, MORPHEUS relies on a masked modeling objective applied to randomly selected omics portions, encouraging the model to learn biologically meaningful cross-modal relationships. The same pre-trained network can be applied to histopathology alone or in combination with any subset of omics modalities, seamlessly adapting to the available inputs. Additionally, MORPHEUS enables any-to-any omics generation, enabling one or more omics profiles to be inferred from any subset of modalities, including H&E alone. Pre-trained on a large pan-cancer cohort, MORPHEUS consistently outperforms state-of-the-art methods across diverse modality combinations and tasks, positioning itself as a promising framework for developing multimodal foundation models in oncology. The code is available at: https://github.com/Lucas-rbnt/MORPHEUS

[Arxiv](https://arxiv.org/abs/2508.00969)