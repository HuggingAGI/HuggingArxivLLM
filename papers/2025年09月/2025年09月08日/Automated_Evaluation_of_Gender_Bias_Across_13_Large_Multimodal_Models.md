# # 13个大型多模态模型性别偏见的自动化评估

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Automated Evaluation of Gender Bias Across 13 Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）彻底革新了文本到图像生成技术，却可能延续训练数据中潜藏的有害社会偏见。尽管已有研究指出这些模型存在性别偏见，但受限于研究方法，难以开展大规模、可比较的跨模型分析。为解决这一问题，我们提出了Aymara图像公平性评估基准，专门用于衡量AI生成图像中的社会偏见。我们针对13个商用LMM，使用75个程序化生成的性别中立提示词，生成从事典型男性职业、典型女性职业及非典型职业的人物图像，随后借助经过验证的LLM裁判系统，对965张生成图像的性别表征进行评分。研究结果显示（所有情况【数学公式】）：1）与现实劳动力数据相比，LMM不仅系统性复制，甚至放大了职业性别刻板印象——在典型男性职业图像中，男性占比高达93.0%，而在典型女性职业图像中男性仅占22.5%；2）模型存在显著的“默认男性”偏见，非典型职业中男性生成占比达68.3%；3）不同模型的偏见程度差异悬殊，总体男性表征比例介于46.7%至73.3%之间。值得关注的是，表现最优的模型显著减少了性别刻板印象，接近性别平等，公平性得分最高。这种差异表明，高偏见并非必然结果，而是设计选择所致。本研究首次提供了迄今为止最全面的跨模型性别偏见评估基准，同时强调了标准化、自动化评估工具对推动AI开发问责与公平的重要性。

> Large multimodal models (LMMs) have revolutionized text-to-image generation, but they risk perpetuating the harmful social biases in their training data. Prior work has identified gender bias in these models, but methodological limitations prevented large-scale, comparable, cross-model analysis. To address this gap, we introduce the Aymara Image Fairness Evaluation, a benchmark for assessing social bias in AI-generated images. We test 13 commercially available LMMs using 75 procedurally-generated, gender-neutral prompts to generate people in stereotypically-male, stereotypically-female, and non-stereotypical professions. We then use a validated LLM-as-a-judge system to score the 965 resulting images for gender representation. Our results reveal (p < .001 for all): 1) LMMs systematically not only reproduce but actually amplify occupational gender stereotypes relative to real-world labor data, generating men in 93.0% of images for male-stereotyped professions but only 22.5% for female-stereotyped professions; 2) Models exhibit a strong default-male bias, generating men in 68.3% of the time for non-stereotyped professions; and 3) The extent of bias varies dramatically across models, with overall male representation ranging from 46.7% to 73.3%. Notably, the top-performing model de-amplified gender stereotypes and approached gender parity, achieving the highest fairness scores. This variation suggests high bias is not an inevitable outcome but a consequence of design choices. Our work provides the most comprehensive cross-model benchmark of gender bias to date and underscores the necessity of standardized, automated evaluation tools for promoting accountability and fairness in AI development.

[Arxiv](https://arxiv.org/abs/2509.07050)