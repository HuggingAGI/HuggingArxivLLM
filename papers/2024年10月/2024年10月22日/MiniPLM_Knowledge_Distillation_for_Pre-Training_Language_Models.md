# MiniPLM: 预训练语言模型的知识蒸馏

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何通过知识蒸馏（KD）技术，利用大型教师语言模型（LMs）来训练小型高性能学生语言模型。虽然涉及到模型训练和优化，但其核心应用场景是利用大型语言模型（LLM）来提升小型模型的性能，因此属于LLM应用的范畴。` `机器学习`

> MiniPLM: Knowledge Distillation for Pre-Training Language Models

# 摘要

> # 摘要
知识蒸馏（KD）常用于利用大型教师语言模型（LMs）训练小型高性能学生语言模型。然而，预训练阶段的KD在效率、灵活性和效果上存在挑战。现有方法要么因在线教师推理导致高计算成本，要么要求教师与学生LMs的标记化匹配，要么可能丢失教师生成数据的难度和多样性。为此，我们提出了MiniPLM，一个通过教师知识优化训练数据分布的KD框架。MiniPLM通过离线教师推理提高效率，支持多学生LMs的KD而不增加训练成本；通过仅操作训练语料库实现跨模型家族的KD；通过利用大小LMs的差异增强数据难度和多样性，帮助学生LMs掌握复杂知识。实验表明，MiniPLM在9个下游任务上提升了学生LMs的性能，增强了语言建模能力，并减少了预训练计算。缩放曲线外推显示，MiniPLM的优势在大规模预训练中依然显著。进一步分析表明，MiniPLM支持跨模型家族的KD，并提高了预训练数据的利用率。模型、代码和数据详见https://github.com/thu-coai/MiniPLM。

> Knowledge distillation (KD) is widely used to train small, high-performing student language models (LMs) using large teacher LMs. While effective in fine-tuning, KD during pre-training faces challenges in efficiency, flexibility, and effectiveness. Existing methods either incur high computational costs due to online teacher inference, require tokenization matching between teacher and student LMs, or risk losing the difficulty and diversity of the teacher-generated training data. To address these issues, we propose MiniPLM, a KD framework for pre-training LMs by refining the training data distribution with the teacher's knowledge. For efficiency, MiniPLM performs offline teacher LM inference, allowing KD for multiple student LMs without adding training-time costs. For flexibility, MiniPLM operates solely on the training corpus, enabling KD across model families. For effectiveness, MiniPLM leverages the differences between large and small LMs to enhance the difficulty and diversity of the training data, helping student LMs acquire versatile and sophisticated knowledge. Extensive experiments demonstrate that MiniPLM boosts the student LMs' performance on 9 widely used downstream tasks, improves the language modeling capabilities, and reduces pre-training computation. The benefit of MiniPLM extends to large pre-training scales, evidenced by the extrapolation of the scaling curves. Further analysis reveals that MiniPLM supports KD across model families and enhances the utilization of pre-training data. Our model, code, and data are available at https://github.com/thu-coai/MiniPLM.

[Arxiv](https://arxiv.org/abs/2410.17215)