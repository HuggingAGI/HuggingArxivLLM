# MultiEYE：用于眼底图像中 OCT 增强型视网膜疾病识别的数据集与基准

发布时间：2024年12月12日

`其他` `眼病诊断`

> MultiEYE: Dataset and Benchmark for OCT-Enhanced Retinal Disease Recognition from Fundus Images

# 摘要

> 现有的针对眼底和 OCT 图像的多模态学习方法，大多要求两种模态都具备且严格配对来进行训练和测试，这在临床情境中不太实际。为拓展临床应用范畴，我们构建了一个全新的设定——“基于眼底图像的 OCT 增强疾病识别”，此设定允许在训练阶段使用未配对的多模态数据，并依靠广泛的眼底照片进行测试。为了给这个设定设立基准，我们推出了首个用于眼病诊断的大型多模态多类数据集 MultiEYE，并提出了 OCT 辅助概念蒸馏法（OCT-CoDA），它借助语义丰富的概念从 OCT 图像中提取疾病相关知识，并将其运用到眼底模型中。具体来说，我们把图像-概念关系当作将有用知识从 OCT 教师模型提炼到底部学生模型的纽带，这极大地提升了基于眼底图像的诊断性能，并将跨模态知识转移转化为一个可解释的过程。通过对多疾病分类任务的大量实验，我们提出的 OCT-CoDA 展现出了出色的结果和可解释性，在临床应用方面显示出巨大潜力。我们的数据集和代码可在 https://github.com/xmed-lab/MultiEYE 获取。

> Existing multi-modal learning methods on fundus and OCT images mostly require both modalities to be available and strictly paired for training and testing, which appears less practical in clinical scenarios. To expand the scope of clinical applications, we formulate a novel setting, "OCT-enhanced disease recognition from fundus images", that allows for the use of unpaired multi-modal data during the training phase and relies on the widespread fundus photographs for testing. To benchmark this setting, we present the first large multi-modal multi-class dataset for eye disease diagnosis, MultiEYE, and propose an OCT-assisted Conceptual Distillation Approach (OCT-CoDA), which employs semantically rich concepts to extract disease-related knowledge from OCT images and leverage them into the fundus model. Specifically, we regard the image-concept relation as a link to distill useful knowledge from the OCT teacher model to the fundus student model, which considerably improves the diagnostic performance based on fundus images and formulates the cross-modal knowledge transfer into an explainable process. Through extensive experiments on the multi-disease classification task, our proposed OCT-CoDA demonstrates remarkable results and interpretability, showing great potential for clinical application. Our dataset and code are available at https://github.com/xmed-lab/MultiEYE.

[Arxiv](https://arxiv.org/abs/2412.09402)