# 伸出援手：基于多语言模型的手势驱动半监督提示语音识别，助力无障碍交流

发布时间：2025年03月11日

`LLM应用` `听力障碍` `视觉交流`

> Lend a Hand: Semi Training-Free Cued Speech Recognition via MLLM-Driven Hand Modeling for Barrier-free Communication

# 摘要

> 唇读编码（CS）是一项融合了唇读与手形编码的创新性视觉交流系统，旨在提升听力障碍者之间的有效沟通。自动CS识别（ACSR）指的是通过AI技术自动识别CS中的手势与口型，并将其转化为文字的过程。然而，以往的研究通常依赖于复杂的融合模块和训练技巧，且受限于CS数据量有限，手部特征提取及识别建模效果一直不尽如人意，这极大地限制了ACSR的实际效果。

为解决这一问题，我们创新性地探索了多模态大型语言模型（MLLMs）在CS手部形状和位置识别方面的潜力。具体而言，我们提出了一种全新的半无监督训练范式——STF-ACSR。该方法通过中文CS提示模块（CCSPM）实现了手部动作的零样本识别，该模块基于MLLM实现了无监督关键帧筛选和定制化提示工程。随后，通过简约融合模块（MFM）将识别结果与唇读模型相结合，从而实现卓越的识别效果。

此外，为支持本次研究，我们补充了现有数据集，新增了8位听力障碍者的CS引导数据，与原有6位正常听力引导者的数据共同组成了新的混合数据集。大量实验证明，STF-ACSR在正常听力者与听力障碍者数据上的表现均显著优于以往方法。实现代码与检查点已开源，地址为https://github.com/DennisHgj/STF_ACSR。

> Cued Speech (CS) is an innovative visual communication system that integrates lip-reading with hand coding, designed to enhance effective communication for individuals with hearing impairments. Automatic CS Recognition (ACSR) refers to the AI-driven process of automatically recognizing hand gestures and lip movements in CS, converting them into text. However, previous work often relies on complex fusion modules and training techniques. Additionally, due to the limited amount of data in CS, the extraction of hand features, as well as recognition modeling, has consistently been subpar, significantly limiting the effectiveness of ACSR. To address this issue, we have innovatively explored the capabilities of Multimodal large language models (MLLMs) in recognizing hand shapes and positions in CS. More precisely, we propose a new Semi Training-Free paradigm for ACSR, named STF-ACSR. This approach leverages zero-shot recognition of hand movements through the Chinese CS Prompt Module (CCSPM), which equipped a training-free keyframe filtering and customized prompt engineering based on MLLM. It then integrates the recognition results into the lip-reading model using a Minimalist Fusion Module (MFM), effectively achieving superior recognition results. Furthermore, specifically for this study, we have supplemented the existing dataset of 6 normal hearing CS cuers by recording additional data from 8 cuers with hearing impairments, resulting in a new mixed dataset. Extensive experiments have demonstrated that STF-ACSR significantly outperforms previous methods on both normal and hearing-impaired data. Implementation and checkpoints are available at https://github.com/DennisHgj/STF_ACSR.

[Arxiv](https://arxiv.org/abs/2503.21785)