# 基于语义场景图的超声图像解释与扫查指导

发布时间：2025年06月24日

`LLM应用` `医学超声` `场景图`

> Semantic Scene Graph for Ultrasound Image Explanation and Scanning Guidance

# 摘要

> 医学超声图像的理解一直是个难题，主要因为成像和采集参数的差异导致显著的视觉变异性。近期，大型语言模型（LLMs）的进步被用于生成术语丰富的摘要，帮助临床医生更好地理解图像。然而，非专业人士用户（如床旁诊疗场景中的用户）对提升超声可解释性和基础扫描指导的需求尚未得到充分探索。本研究中，我们首次引入场景图（SG）用于超声图像，旨在向普通用户解释图像内容并提供超声扫描指导。我们创新性地采用基于Transformer的一阶段方法计算超声SG，无需显式的物体检测步骤。为了生成更易于普通用户理解的图像解释，我们利用用户查询通过LLMs进一步优化抽象的SG表示。此外，我们探索了预测SG在引导超声扫描以寻找当前成像视野中缺失解剖结构方面的潜力，帮助普通用户实现更标准化和全面的解剖探索。我们在五名志愿者的左、右颈部区域图像上验证了这一基于SG的图像解释和扫描指导方法的有效性，包括颈动脉和甲状腺。实验结果表明，该方法通过提升超声图像的可解释性和易用性，具有极大潜力使超声技术更加普及，惠及普通用户。

> Understanding medical ultrasound imaging remains a long-standing challenge due to significant visual variability caused by differences in imaging and acquisition parameters. Recent advancements in large language models (LLMs) have been used to automatically generate terminology-rich summaries orientated to clinicians with sufficient physiological knowledge. Nevertheless, the increasing demand for improved ultrasound interpretability and basic scanning guidance among non-expert users, e.g., in point-of-care settings, has not yet been explored. In this study, we first introduce the scene graph (SG) for ultrasound images to explain image content to ordinary and provide guidance for ultrasound scanning. The ultrasound SG is first computed using a transformer-based one-stage method, eliminating the need for explicit object detection. To generate a graspable image explanation for ordinary, the user query is then used to further refine the abstract SG representation through LLMs. Additionally, the predicted SG is explored for its potential in guiding ultrasound scanning toward missing anatomies within the current imaging view, assisting ordinary users in achieving more standardized and complete anatomical exploration. The effectiveness of this SG-based image explanation and scanning guidance has been validated on images from the left and right neck regions, including the carotid and thyroid, across five volunteers. The results demonstrate the potential of the method to maximally democratize ultrasound by enhancing its interpretability and usability for ordinaries.

[Arxiv](https://arxiv.org/abs/2506.19683)