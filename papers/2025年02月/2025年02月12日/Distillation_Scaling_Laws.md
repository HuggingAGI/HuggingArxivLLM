# 蒸馏缩放定律

发布时间：2025年02月12日

`LLM理论` `人工智能` `机器学习`

> Distillation Scaling Laws

# 摘要

> 我们提出了一个蒸馏缩放定律，根据计算预算及其分配比例，可以准确预测蒸馏模型的性能。这一发现大大降低了大规模蒸馏应用中的风险，使我们能够通过优化教师模型和学生模型的计算资源分配，来最大化学生模型的表现。我们为两种情况提供了计算最优的蒸馏配方：1）当已有教师模型可用，或 2）需要先训练教师模型。如果需要蒸馏多个学生模型，或者教师模型已经存在，蒸馏法的表现将优于监督预训练，直到一个与学生模型规模可预测增长的计算水平。但如果仅蒸馏一个学生模型，并且同时需要训练教师模型，则建议直接采用监督学习。此外，我们还分享了大规模蒸馏研究的深入洞察，这些发现不仅深化了我们对蒸馏法的理解，也为未来的实验设计提供了宝贵的指导。

> We provide a distillation scaling law that estimates distilled model performance based on a compute budget and its allocation between the student and teacher. Our findings reduce the risks associated with using distillation at scale; compute allocation for both the teacher and student models can now be done to maximize student performance. We provide compute optimal distillation recipes for when 1) a teacher exists, or 2) a teacher needs training. If many students are to be distilled, or a teacher already exists, distillation outperforms supervised pretraining until a compute level which grows predictably with student size. If one student is to be distilled and a teacher also needs training, supervised learning should be done instead. Additionally, we provide insights across our large scale study of distillation, which increase our understanding of distillation and inform experimental design.

[Arxiv](https://arxiv.org/abs/2502.08606)