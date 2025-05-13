# KDH-MLTC：面向医疗领域的多标签文本分类知识蒸馏。

发布时间：2025年05月11日

`LLM应用` `文本分类`

> KDH-MLTC: Knowledge Distillation for Healthcare Multi-Label Text Classification

# 摘要

> 面对日益增长的医疗文本数据，我们需要一种既能高效计算又能精准分类的方法，以应对医学术语的复杂性。本研究提出了医疗多标签文本分类知识蒸馏（KDH-MLTC）框架，巧妙结合模型压缩与大语言模型（LLMs）。通过知识蒸馏与序列微调的创新结合，并借助粒子群优化（PSO）进行超参数调优，KDH-MLTC有效解决了传统医疗多标签文本分类（MLTC）的难题。该框架通过序列训练将复杂教师模型（如BERT）的知识迁移到轻量级学生模型（如DistilBERT），在保留原有知识的同时大幅降低计算成本，使分类本地化成为可能，确保医疗数据的敏感性符合HIPAA标准。实验结果表明，在癌症标志（HoC）数据集的三个不同规模的医学文献数据集上，KDH-MLTC的表现超越现有方法，尤其在最大数据集上达到了82.70%的F1分数。统计验证和消融研究进一步证明了其鲁棒性，而PSO优化则帮助找到了最佳配置。KDH-MLTC在医疗文本分类领域实现了效率与精度的完美平衡，为资源有限的医疗环境提供了理想解决方案。

> The increasing volume of healthcare textual data requires computationally efficient, yet highly accurate classification approaches able to handle the nuanced and complex nature of medical terminology. This research presents Knowledge Distillation for Healthcare Multi-Label Text Classification (KDH-MLTC), a framework leveraging model compression and Large Language Models (LLMs). The proposed approach addresses conventional healthcare Multi-Label Text Classification (MLTC) challenges by integrating knowledge distillation and sequential fine-tuning, subsequently optimized through Particle Swarm Optimization (PSO) for hyperparameter tuning. KDH-MLTC transfers knowledge from a more complex teacher LLM (i.e., BERT) to a lighter student LLM (i.e., DistilBERT) through sequential training adapted to MLTC that preserves the teacher's learned information while significantly reducing computational requirements. As a result, the classification is enabled to be conducted locally, making it suitable for healthcare textual data characterized by sensitivity and, therefore, ensuring HIPAA compliance. The experiments conducted on three medical literature datasets of different sizes, sampled from the Hallmark of Cancer (HoC) dataset, demonstrate that KDH-MLTC achieves superior performance compared to existing approaches, particularly for the largest dataset, reaching an F1 score of 82.70%. Additionally, statistical validation and an ablation study are carried out, proving the robustness of KDH-MLTC. Furthermore, the PSO-based hyperparameter optimization process allowed the identification of optimal configurations. The proposed approach contributes to healthcare text classification research, balancing efficiency requirements in resource-constrained healthcare settings with satisfactory accuracy demands.

[Arxiv](https://arxiv.org/abs/2505.07162)