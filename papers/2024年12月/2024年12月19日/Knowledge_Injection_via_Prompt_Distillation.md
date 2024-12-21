# 通过提示蒸馏进行知识注入

发布时间：2024年12月19日

`RAG` `语言模型` `知识注入`

> Knowledge Injection via Prompt Distillation

# 摘要

> 在众多实际应用里，大型语言模型（LLMs）得融入预训练数据里没有的新知识。达成此目的的主要手段是微调与检索增强生成（RAG）。虽说 RAG 已成知识注入的行业标准，可微调还未取得同等的成功。在本文中，我们提出了一种用于学习新知识的新型微调技术，并表明其能达到 RAG 的性能。所提方法基于自蒸馏方式，我们称其为提示蒸馏。首先，我们生成有关新知识的问答对。接着，我们在问答对上对学生模型进行微调，使其模仿教师模型的输出分布，而教师模型在其提示中额外接收了新知识。学生模型和教师模型相同，只是配备了一个 LoRA 适配器。这种训练流程有助于将教师提示中的新知识蒸馏到学生模型的权重里。

> In many practical applications, large language models (LLMs) need to incorporate new knowledge not present in their pre-training data. The primary methods for this are fine-tuning and retrieval-augmented generation (RAG). Although RAG has emerged as the industry standard for knowledge injection, fine-tuning has not yet achieved comparable success. In this paper, we propose a new fine-tuning technique for learning new knowledge and show that it can reach the performance of RAG. The proposed method is based on the self-distillation approach, which we call prompt distillation. First, we generate question-answer pairs about the new knowledge. Then, we fine-tune a student model on the question-answer pairs to imitate the output distributions of a teacher model, which additionally receives the new knowledge in its prompt. The student model is identical to the teacher, except it is equipped with a LoRA adapter. This training procedure facilitates distilling the new knowledge from the teacher's prompt into the student's weights.

[Arxiv](https://arxiv.org/abs/2412.14964)