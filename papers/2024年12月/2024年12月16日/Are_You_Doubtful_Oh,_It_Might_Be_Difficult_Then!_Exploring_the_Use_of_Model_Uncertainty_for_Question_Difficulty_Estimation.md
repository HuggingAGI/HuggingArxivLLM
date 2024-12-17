# 你心存疑虑？哦，那或许会有难度！探究模型不确定性在问题难度估算中的运用

发布时间：2024年12月16日

`LLM应用`

> Are You Doubtful? Oh, It Might Be Difficult Then! Exploring the Use of Model Uncertainty for Question Difficulty Estimation

# 摘要

> 在教育场景中，多项选择题（MCQs）难度的评估（这是衡量学习进展的常用手段）对师生而言都极为有用。鉴于从多方面来看人工评估成本颇高，针对多项选择题项目难度估计的自动方法已被研究，然而迄今成果喜忧参半。我们处理此问题的方式与过往工作有所不同：让各类大型语言模型去解答两个不同的多项选择题数据集中的问题，借助模型的不确定性来估算项目难度。通过在随机森林回归器中同时运用模型不确定性特征和文本特征，我们发现不确定性特征对难度预测贡献显著，且难度与能正确回答问题的学生数量成反比。除展现我们方法的价值外，我们还发现我们的模型在 BEA 公开数据集上达到了最先进的水平。

> In an educational setting, an estimate of the difficulty of multiple-choice questions (MCQs), a commonly used strategy to assess learning progress, constitutes very useful information for both teachers and students. Since human assessment is costly from multiple points of view, automatic approaches to MCQ item difficulty estimation are investigated, yielding however mixed success until now. Our approach to this problem takes a different angle from previous work: asking various Large Language Models to tackle the questions included in two different MCQ datasets, we leverage model uncertainty to estimate item difficulty. By using both model uncertainty features as well as textual features in a Random Forest regressor, we show that uncertainty features contribute substantially to difficulty prediction, where difficulty is inversely proportional to the number of students who can correctly answer a question. In addition to showing the value of our approach, we also observe that our model achieves state-of-the-art results on the BEA publicly available dataset.

[Arxiv](https://arxiv.org/abs/2412.11831)