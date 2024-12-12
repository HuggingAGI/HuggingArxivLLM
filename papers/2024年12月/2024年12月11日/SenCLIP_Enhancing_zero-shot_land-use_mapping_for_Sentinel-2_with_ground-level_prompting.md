# SenCLIP：借助地面提示提升 Sentinel-2 的零样本土地利用测绘能力

发布时间：2024年12月11日

`LLM应用` `卫星图像`

> SenCLIP: Enhancing zero-shot land-use mapping for Sentinel-2 with ground-level prompting

# 摘要

> 预训练的视觉语言模型（VLMs），像 CLIP 这种，凭借自由形式的提示展现出了出色的零样本分类能力，甚至在特定领域有一定的泛化表现。但由于其训练集中卫星图像数据占比少（主要是地面图像），所以在卫星图像方面的性能受限。现有的卫星图像提示技术往往局限于“卫星图像……”这类通用表述，这限制了它们在零样本土地利用和土地覆盖（LULC）映射中的效果。为解决这些难题，我们推出了 SenCLIP，它借助大量的 Sentinel-2 图像数据集以及欧洲各地带地理标签的地面照片，把 CLIP 的表征迁移到 Sentinel-2 图像上。我们使用 EuroSAT 和 BigEarthNet 数据集，分别采用空中和地面提示风格，对 SenCLIP 及其他先进的遥感 VLMs 在零样本 LULC 映射任务中进行评估。我们的方法让地面表征与卫星图像相匹配，在两种提示风格下的分类准确率都大幅提升，为在零样本 LULC 映射中运用自由形式的文本描述创造了新机遇。

> Pre-trained vision-language models (VLMs), such as CLIP, demonstrate impressive zero-shot classification capabilities with free-form prompts and even show some generalization in specialized domains. However, their performance on satellite imagery is limited due to the underrepresentation of such data in their training sets, which predominantly consist of ground-level images. Existing prompting techniques for satellite imagery are often restricted to generic phrases like a satellite image of ..., limiting their effectiveness for zero-shot land-use and land-cover (LULC) mapping. To address these challenges, we introduce SenCLIP, which transfers CLIPs representation to Sentinel-2 imagery by leveraging a large dataset of Sentinel-2 images paired with geotagged ground-level photos from across Europe. We evaluate SenCLIP alongside other SOTA remote sensing VLMs on zero-shot LULC mapping tasks using the EuroSAT and BigEarthNet datasets with both aerial and ground-level prompting styles. Our approach, which aligns ground-level representations with satellite imagery, demonstrates significant improvements in classification accuracy across both prompt styles, opening new possibilities for applying free-form textual descriptions in zero-shot LULC mapping.

[Arxiv](https://arxiv.org/abs/2412.08536)