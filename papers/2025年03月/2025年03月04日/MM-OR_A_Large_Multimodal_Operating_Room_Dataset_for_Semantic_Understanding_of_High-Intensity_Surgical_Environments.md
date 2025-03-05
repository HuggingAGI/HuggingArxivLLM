# MM-OR：一个大型多模态手术室数据集，助力高强手术环境的语义理解。

发布时间：2025年03月04日

`其他` `多模态场景分析`

> MM-OR: A Large Multimodal Operating Room Dataset for Semantic Understanding of High-Intensity Surgical Environments

# 摘要

> 手术室是复杂而高风险的环境，精准理解医护人员、工具与设备的互动对于提升手术辅助、环境感知和患者安全至关重要。然而，现有数据集在规模、真实性和多模态性质的捕捉方面存在明显不足，严重制约了手术室建模的发展。为此，我们推出了MM-OR——首个真实且大规模的多模态时空手术室数据集，也是首个支持多模态场景图生成的数据集。MM-OR全面记录了手术室场景，包含RGB-D数据、细节视图、音频、语音转录、机器人日志和追踪数据，并标注了全景分割、语义场景图和下游任务标签。此外，我们还提出了MM2SG——首个用于场景图生成的多模态大规模视觉-语言模型。通过大量实验，我们验证了其有效利用多模态输入的能力。MM-OR和MM2SG共同为全面理解手术室环境设立了新基准，为复杂、高风险环境中的多模态场景分析开辟了道路。我们的代码和数据可在GitHub获取：https://github.com/egeozsoy/MM-OR。

> Operating rooms (ORs) are complex, high-stakes environments requiring precise understanding of interactions among medical staff, tools, and equipment for enhancing surgical assistance, situational awareness, and patient safety. Current datasets fall short in scale, realism and do not capture the multimodal nature of OR scenes, limiting progress in OR modeling. To this end, we introduce MM-OR, a realistic and large-scale multimodal spatiotemporal OR dataset, and the first dataset to enable multimodal scene graph generation. MM-OR captures comprehensive OR scenes containing RGB-D data, detail views, audio, speech transcripts, robotic logs, and tracking data and is annotated with panoptic segmentations, semantic scene graphs, and downstream task labels. Further, we propose MM2SG, the first multimodal large vision-language model for scene graph generation, and through extensive experiments, demonstrate its ability to effectively leverage multimodal inputs. Together, MM-OR and MM2SG establish a new benchmark for holistic OR understanding, and open the path towards multimodal scene analysis in complex, high-stakes environments. Our code, and data is available at https://github.com/egeozsoy/MM-OR.

[Arxiv](https://arxiv.org/abs/2503.02579)