# RetinaLogos：借助图像描述实现高分辨率眼底图像的精细合成

发布时间：2025年05月19日

`LLM应用` `图像生成`

> RetinaLogos: Fine-Grained Synthesis of High-Resolution Retinal Images Through Captions

# 摘要

> 眼科机器学习模型开发面临一个重大挑战：高质量标注的视网膜图像数据稀缺，这阻碍了该领域的发展。现有用于合成彩色眼底图像（CFP）的方法主要依赖预定义的疾病标签，存在明显局限性。然而，当前方法仍然受限，无法生成涵盖更广泛类别且具有多样和精细解剖结构的图像。

为克服这些挑战，我们首先引入了一个创新的流水线，创建了一个大规模合成的Caption-CFP数据集，包含140万个条目，名为RetinaLogos-1400k。具体来说，RetinaLogos-1400k使用大型语言模型（LLMs）来描述视网膜状况和关键结构，如视盘配置、血管分布、神经纤维层和病理特征。

此外，基于此数据集，我们采用了一种名为RetinaLogos的新三步训练框架，该框架能够实现对视网膜图像的精细语义控制，并准确捕捉疾病进展的不同阶段、细微的解剖变异和特定的病变类型。

大量实验表明，在多个数据集上，该方法达到了最先进的性能水平，其中62.07%的文本驱动合成图像无法被眼科医生与真实图像区分开来。此外，合成数据将糖尿病视网膜病变分级和青光眼检测的准确性提高了10%-25%，从而为扩充眼科数据集提供了一种可扩展的解决方案。

> The scarcity of high-quality, labelled retinal imaging data, which presents a significant challenge in the development of machine learning models for ophthalmology, hinders progress in the field. To synthesise Colour Fundus Photographs (CFPs), existing methods primarily relying on predefined disease labels face significant limitations. However, current methods remain limited, thus failing to generate images for broader categories with diverse and fine-grained anatomical structures. To overcome these challenges, we first introduce an innovative pipeline that creates a large-scale, synthetic Caption-CFP dataset comprising 1.4 million entries, called RetinaLogos-1400k. Specifically, RetinaLogos-1400k uses large language models (LLMs) to describe retinal conditions and key structures, such as optic disc configuration, vascular distribution, nerve fibre layers, and pathological features. Furthermore, based on this dataset, we employ a novel three-step training framework, called RetinaLogos, which enables fine-grained semantic control over retinal images and accurately captures different stages of disease progression, subtle anatomical variations, and specific lesion types. Extensive experiments demonstrate state-of-the-art performance across multiple datasets, with 62.07% of text-driven synthetic images indistinguishable from real ones by ophthalmologists. Moreover, the synthetic data improves accuracy by 10%-25% in diabetic retinopathy grading and glaucoma detection, thereby providing a scalable solution to augment ophthalmic datasets.

[Arxiv](https://arxiv.org/abs/2505.12887)