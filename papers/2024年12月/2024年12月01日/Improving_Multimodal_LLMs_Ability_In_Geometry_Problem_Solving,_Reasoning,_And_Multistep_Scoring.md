# 提升多模态大型语言模型在几何问题求解、推理及多步骤评分上的能力

发布时间：2024年12月01日

`LLM应用`

> Improving Multimodal LLMs Ability In Geometry Problem Solving, Reasoning, And Multistep Scoring

# 摘要

> 这篇论文推出了 GPSM4K，一个专为提升大型视觉语言模型（LVLMs）解题能力而打造的综合性几何多模态数据集。GPSM4K 涵盖了从 7 至 12 年级数学教材中人工提取的 2157 个多模态问答对，并进一步扩充至 5340 个问题，包含数值和定理证明类问题。不像 PGPS9k、Geometry3K 以及 Geo170K 只具有客观题型，GPSM4K 以统一格式提供了详尽的分步解答，利于对解题方法进行全面评估。此数据集是衡量 LVLMs 几何推理能力的绝佳基准。对我们测试集的评估显示，开源语言模型在几何问题解决上尚有提升空间。在我们的训练集上进行微调能增强模型的几何解题能力。另外，我们还评估了图像描述和检索增强生成（RAG）等技术对模型性能的效果。我们借助 LLM，通过提供标准答案和预测答案来自动完成最终答案评估的任务。这项研究有助于评估和提升 LVLMs 的几何推理能力。

> This paper presents GPSM4K, a comprehensive geometry multimodal dataset tailored to augment the problem-solving capabilities of Large Vision Language Models (LVLMs). GPSM4K encompasses 2157 multimodal question-answer pairs manually extracted from mathematics textbooks spanning grades 7-12 and is further augmented to 5340 problems, consisting of both numerical and theorem-proving questions. In contrast to PGPS9k, Geometry3K, and Geo170K which feature only objective-type questions, GPSM4K offers detailed step-by-step solutions in a consistent format, facilitating a comprehensive evaluation of problem-solving approaches. This dataset serves as an excellent benchmark for assessing the geometric reasoning capabilities of LVLMs. Evaluation of our test set shows that there is scope for improvement needed in open-source language models in geometry problem-solving. Finetuning on our training set increases the geometry problem-solving capabilities of models. Further, We also evaluate the effectiveness of techniques such as image captioning and Retrieval Augmentation generation (RAG) on model performance. We leveraged LLM to automate the task of final answer evaluation by providing ground truth and predicted solutions. This research will help to assess and improve the geometric reasoning capabilities of LVLMs.

[Arxiv](https://arxiv.org/abs/2412.00846)