# SPEX: 一款用于光谱遥感图像地表覆盖提取的视觉-语言模型

发布时间：2025年08月07日

`LLM应用` `人工智能`

> SPEX: A Vision-Language Model for Land Cover Extraction on Spectral Remote Sensing Images

# 摘要

> 光谱信息在遥感观测中扮演着关键角色。尽管已有众多视觉-语言模型用于像素级分析，但光谱信息的潜力仍未得到充分发挥，尤其在多光谱应用中表现欠佳。为突破这一限制，我们开发了一个名为SPIE的视觉-语言指令遵循数据集，该数据集基于经典光谱指数计算，将地物覆盖的光谱特性转化为大型语言模型（LLMs）可理解的文本描述。基于此，我们提出了一种专为土地覆盖提取设计的多模态LLM——SPEX。通过精心设计的多尺度特征聚合、令牌上下文浓缩和多光谱视觉预训练等组件与策略，SPEX实现了精准且灵活的像素级分析。据我们所知，SPEX是首个专注于光谱遥感图像土地覆盖提取的多模态视觉-语言模型。在五个公共多光谱数据集上的实验表明，SPEX在提取植被、建筑物和水体等典型地物类别方面超越了现有最优方法。此外，SPEX能够提供预测的文本解释，增强了结果的可解释性和用户体验。项目代码即将开源：https://github.com/MiliLab/SPEX。


> Spectral information has long been recognized as a critical cue in remote sensing observations. Although numerous vision-language models have been developed for pixel-level interpretation, spectral information remains underutilized, resulting in suboptimal performance, particularly in multispectral scenarios. To address this limitation, we construct a vision-language instruction-following dataset named SPIE, which encodes spectral priors of land-cover objects into textual attributes recognizable by large language models (LLMs), based on classical spectral index computations. Leveraging this dataset, we propose SPEX, a multimodal LLM designed for instruction-driven land cover extraction. To this end, we introduce several carefully designed components and training strategies, including multiscale feature aggregation, token context condensation, and multispectral visual pre-training, to achieve precise and flexible pixel-level interpretation. To the best of our knowledge, SPEX is the first multimodal vision-language model dedicated to land cover extraction in spectral remote sensing imagery. Extensive experiments on five public multispectral datasets demonstrate that SPEX consistently outperforms existing state-of-the-art methods in extracting typical land cover categories such as vegetation, buildings, and water bodies. Moreover, SPEX is capable of generating textual explanations for its predictions, thereby enhancing interpretability and user-friendliness. Code will be released at: https://github.com/MiliLab/SPEX.

[Arxiv](https://arxiv.org/abs/2508.05202)