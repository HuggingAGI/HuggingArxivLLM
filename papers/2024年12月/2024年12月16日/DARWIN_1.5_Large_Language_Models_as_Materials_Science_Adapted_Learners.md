# DARWIN 1.5：大型语言模型成为材料科学的适应型学习者

发布时间：2024年12月16日

`LLM应用` `材料科学` `语言模型`

> DARWIN 1.5: Large Language Models as Materials Science Adapted Learners

# 摘要

> 材料的发现与设计旨在于高度复杂且多样的搜索空间里寻觅具备理想特性的成分和结构。传统的解决办法，像高通量模拟和机器学习（ML），往往依赖复杂的描述符，这阻碍了其在跨任务中的通用性和可转移性。而且，由于现实中不可避免的缺陷和纯度问题，这些描述符可能偏离实验数据，或许会降低其在实际应用中的成效。为应对此类挑战，我们推出了 Darwin 1.5，这是一个专为材料科学打造的开源大型语言模型（LLM）。凭借利用自然语言作为输入，Darwin 无需特定任务的描述符，实现了灵活且统一的材料特性预测与发现方式。我们采用了两阶段的训练策略，将问答（QA）微调与多任务学习（MTL）相结合，在各种模式中注入特定领域的知识，并促进跨任务知识的转移。通过我们的策略，我们大幅提升了 LLM 的预测准确率，与 LLaMA-7B 基础模型相比，最大提升了 60％。它在材料科学的各类任务中表现更优，展现了 LLM 为材料发现和设计提供更具通用性和可扩展性基础模型的潜力。

> Materials discovery and design aim to find components and structures with desirable properties over highly complex and diverse search spaces. Traditional solutions, such as high-throughput simulations and machine learning (ML), often rely on complex descriptors, which hinder generalizability and transferability across tasks. Moreover, these descriptors may deviate from experimental data due to inevitable defects and purity issues in the real world, which may reduce their effectiveness in practical applications. To address these challenges, we propose Darwin 1.5, an open-source large language model (LLM) tailored for materials science. By leveraging natural language as input, Darwin eliminates the need for task-specific descriptors and enables a flexible, unified approach to material property prediction and discovery. We employ a two-stage training strategy combining question-answering (QA) fine-tuning with multi-task learning (MTL) to inject domain-specific knowledge in various modalities and facilitate cross-task knowledge transfer. Through our strategic approach, we achieved a significant enhancement in the prediction accuracy of LLMs, with a maximum improvement of 60\% compared to LLaMA-7B base models. It further outperforms traditional machine learning models on various tasks in material science, showcasing the potential of LLMs to provide a more versatile and scalable foundation model for materials discovery and design.

[Arxiv](https://arxiv.org/abs/2412.11970)