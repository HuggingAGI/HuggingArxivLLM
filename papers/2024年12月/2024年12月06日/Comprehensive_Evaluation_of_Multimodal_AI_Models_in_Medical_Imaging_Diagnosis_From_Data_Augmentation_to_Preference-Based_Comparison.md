# 对医学影像诊断中的多模态 AI 模型进行全面评估：从数据增强到基于偏好的比较

发布时间：2024年12月06日

`LLM应用` `医学成像` `诊断评估`

> Comprehensive Evaluation of Multimodal AI Models in Medical Imaging Diagnosis: From Data Augmentation to Preference-Based Comparison

# 摘要

> 本研究为医学成像诊断中的多模态模型引入了一套评估框架。我们打造了一个涵盖数据预处理、模型推断和基于偏好的评估的流程，通过受控增强将最初的 500 例临床病例拓展至 3000 例。我们的方法把医学图像和临床观察相结合来生成评估结果，并使用 Claude 3.5 Sonnet 针对医生撰写的诊断进行独立评估。结果显示，不同模型的表现各异，Llama 3.2 - 90B 在 85.27％的病例中表现优于人类诊断。相较而言，BLIP2 和 Llava 等专业视觉模型在 41.36％和 46.77％的病例中分别呈现出偏好。此框架凸显了大型多模态模型在某些任务中超越人类诊断的可能性。

> This study introduces an evaluation framework for multimodal models in medical imaging diagnostics. We developed a pipeline incorporating data preprocessing, model inference, and preference-based evaluation, expanding an initial set of 500 clinical cases to 3,000 through controlled augmentation. Our method combined medical images with clinical observations to generate assessments, using Claude 3.5 Sonnet for independent evaluation against physician-authored diagnoses. The results indicated varying performance across models, with Llama 3.2-90B outperforming human diagnoses in 85.27% of cases. In contrast, specialized vision models like BLIP2 and Llava showed preferences in 41.36% and 46.77% of cases, respectively. This framework highlights the potential of large multimodal models to outperform human diagnostics in certain tasks.

[Arxiv](https://arxiv.org/abs/2412.05536)