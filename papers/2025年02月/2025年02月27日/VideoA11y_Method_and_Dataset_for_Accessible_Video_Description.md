# VideoA11y：可访问视频描述的研究方法与数据集

发布时间：2025年02月27日

`LLM应用` `无障碍` `视频处理`

> VideoA11y: Method and Dataset for Accessible Video Description

# 摘要

> 视频描述对视障人士获取视觉内容至关重要。然而，现有AI模型因训练数据中标注质量的限制，常无法生成完全满足视障人士需求的描述。为解决这一问题，我们提出了VideoA11y方法，该方法结合多模态大型语言模型（MLLMs）和视频无障碍指南，专为视障人士生成定制化描述。通过这种方法，我们整理出VideoA11y-40K数据集，这是目前规模最大、内容最全面的40,000个视频描述数据集，专为视障人士设计。

通过涵盖15个视频类别的严格测试，涉及347名视力正常参与者、40名视障参与者和7名专业描述员，实验结果表明VideoA11y生成的描述优于新手人工标注，并在清晰度、准确性、客观性、描述性和用户满意度方面与专业人工标注相当。我们在VideoA11y-40K数据集上使用标准和自定义指标评估了模型，结果表明经过该数据集微调的MLLMs能够生成高质量的无障碍描述。代码和数据集可在https://people-robots.github.io/VideoA11y获取。


> Video descriptions are crucial for blind and low vision (BLV) users to access visual content. However, current artificial intelligence models for generating descriptions often fall short due to limitations in the quality of human annotations within training datasets, resulting in descriptions that do not fully meet BLV users' needs. To address this gap, we introduce VideoA11y, an approach that leverages multimodal large language models (MLLMs) and video accessibility guidelines to generate descriptions tailored for BLV individuals. Using this method, we have curated VideoA11y-40K, the largest and most comprehensive dataset of 40,000 videos described for BLV users. Rigorous experiments across 15 video categories, involving 347 sighted participants, 40 BLV participants, and seven professional describers, showed that VideoA11y descriptions outperform novice human annotations and are comparable to trained human annotations in clarity, accuracy, objectivity, descriptiveness, and user satisfaction. We evaluated models on VideoA11y-40K using both standard and custom metrics, demonstrating that MLLMs fine-tuned on this dataset produce high-quality accessible descriptions. Code and dataset are available at https://people-robots.github.io/VideoA11y.

[Arxiv](https://arxiv.org/abs/2502.20480)