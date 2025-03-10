# 符号混合专家系统：异质推理中的自适应技能路由

发布时间：2025年03月07日

`LLM应用`

> Symbolic Mixture-of-Experts: Adaptive Skill-based Routing for Heterogeneous Reasoning

# 摘要

> 结合现有的预训练专家LLM是一种有前景的解决大规模多样化任务的可扩展方法。然而，按任务级别选择专家往往过于粗放，因为异构任务可能需要为每个实例选择不同的专长。为了实现自适应的实例级别预训练LLM专家混合，我们提出了Symbolic-MoE，这是一个基于符号、文本驱动且无需梯度的专家混合框架。Symbolic-MoE采用细粒度的选择方法，强调具体技能，例如数学中的代数或生物医学推理中的分子生物学。我们提出了一种基于技能的招募策略，根据专家LLM的优势动态选择最相关的专家集合，以应对多样化的推理任务。每个选定的专家生成自己的推理结果，从而得到k个专家的k个输出，然后由聚合器将这些输出整合成一个高质量的最终响应。聚合器的选择基于其整合多样化推理输出的能力。我们展示了Symbolic-MoE的实例级别专家选择显著提升了性能，但若简单实现可能会带来高昂的计算开销，因为需要频繁加载和卸载模型。为了解决这一问题，我们实施了批推理策略，根据实例分配的专家对其进行分组，每个模型只需加载一次。这使我们能够在一个GPU上集成16个专家模型，时间成本与或优于使用4个GPU的多智能体基线方法。通过在多样化的基准测试（MMLU-Pro、GPQA、AIME和MedMCQA）上进行广泛评估，我们证明Symbolic-MoE在表现上超越了强大的LLM如GPT4o-mini，以及多智能体方法，相较于最佳多智能体基线，绝对平均提升了8.15%。此外，Symbolic-MoE消除了昂贵的多轮讨论需求，在计算量更小的情况下超越了讨论基线。

> Combining existing pre-trained expert LLMs is a promising avenue for scalably tackling large-scale and diverse tasks. However, selecting experts at the task level is often too coarse-grained, as heterogeneous tasks may require different expertise for each instance. To enable adaptive instance-level mixing of pre-trained LLM experts, we propose Symbolic-MoE, a symbolic, text-based, and gradient-free Mixture-of-Experts framework. Symbolic-MoE takes a fine-grained approach to selection by emphasizing skills, e.g., algebra in math or molecular biology in biomedical reasoning. We propose a skill-based recruiting strategy that dynamically selects the most relevant set of expert LLMs for diverse reasoning tasks based on their strengths. Each selected expert then generates its own reasoning, resulting in k outputs from k experts, which are then synthesized into a final high-quality response by an aggregator chosen based on its ability to integrate diverse reasoning outputs. We show that Symbolic-MoE's instance-level expert selection improves performance by a large margin but -- when implemented naively -- can introduce a high computational overhead due to the need for constant model loading and offloading. To address this, we implement a batch inference strategy that groups instances based on their assigned experts, loading each model only once. This allows us to integrate 16 expert models on 1 GPU with a time cost comparable to or better than prior multi-agent baselines using 4 GPUs. Through extensive evaluations on diverse benchmarks (MMLU-Pro, GPQA, AIME, and MedMCQA), we demonstrate that Symbolic-MoE outperforms strong LLMs like GPT4o-mini, as well as multi-agent approaches, with an absolute average improvement of 8.15% over the best multi-agent baseline. Moreover, Symbolic-MoE removes the need for expensive multi-round discussions, outperforming discussion baselines with less computation.

[Arxiv](https://arxiv.org/abs/2503.05641)