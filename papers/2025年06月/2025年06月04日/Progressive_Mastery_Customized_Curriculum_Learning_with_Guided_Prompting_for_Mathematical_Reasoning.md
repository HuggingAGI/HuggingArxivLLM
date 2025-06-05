# 渐进式学习：结合引导式提示的定制化课程学习在数学推理中的研究

发布时间：2025年06月04日

`LLM理论` `数学推理`

> Progressive Mastery: Customized Curriculum Learning with Guided Prompting for Mathematical Reasoning

# 摘要

> 大型语言模型（LLMs）在推理任务中表现卓越，但现有模型的训练后表现受限于样本利用率低效和处理困难样本不够灵活。为解决这些问题，我们提出了定制化课程学习（CCL），一个具有两大创新的新型框架。首先，我们引入了基于模型自适应难度定义的方法，根据每个模型的独特能力定制课程数据集，而非使用预定义的难度指标。其次，我们开发了“引导提示”技术，通过战略性提示动态降低样本难度，从而有效利用那些可能损害模型性能的困难样本。在监督微调和强化学习中的全面实验表明，CCL在五个数学推理基准测试中显著优于均匀训练方法，证实了其在提升样本利用率和模型性能方面对两种训练范式的有效性。

> Large Language Models (LLMs) have achieved remarkable performance across various reasoning tasks, yet post-training is constrained by inefficient sample utilization and inflexible difficulty samples processing. To address these limitations, we propose Customized Curriculum Learning (CCL), a novel framework with two key innovations. First, we introduce model-adaptive difficulty definition that customizes curriculum datasets based on each model's individual capabilities rather than using predefined difficulty metrics. Second, we develop "Guided Prompting," which dynamically reduces sample difficulty through strategic hints, enabling effective utilization of challenging samples that would otherwise degrade performance. Comprehensive experiments on supervised fine-tuning and reinforcement learning demonstrate that CCL significantly outperforms uniform training approaches across five mathematical reasoning benchmarks, confirming its effectiveness across both paradigms in enhancing sample utilization and model performance.

[Arxiv](https://arxiv.org/abs/2506.04065)