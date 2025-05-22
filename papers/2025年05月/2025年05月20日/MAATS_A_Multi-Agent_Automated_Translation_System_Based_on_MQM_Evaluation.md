# MAATS：基于MQM评估的多智能体自动翻译系统

发布时间：2025年05月20日

`Agent` `翻译系统`

> MAATS: A Multi-Agent Automated Translation System Based on MQM Evaluation

# 摘要

> 我们提出了一种名为MAATS的多智能体自动翻译系统，该系统利用多维质量指标框架（MQM）作为精细的信号来进行错误检测和优化。MAATS部署了多个专注于不同MQM类别的专业AI智能体（例如，准确性、流畅性、风格、术语），随后由一个合成智能体整合这些标注信息，通过迭代优化翻译结果。这种设计与传统的依赖自我修正的单智能体方法形成鲜明对比。

经过在多种语言对和大型语言模型（LLMs）上的评估，MAATS在自动评估指标和人工评估中均显著超越了零样本和单智能体基线模型。它在语义准确性、本地化适配以及语言差异较大的语言对上表现尤为突出。定性分析表明，MAATS在多层级错误诊断、多角度遗漏检测和语境感知优化方面具有显著优势。通过将模块化智能体角色与可解释的MQM维度对齐，MAATS缩小了黑箱LLMs与人类翻译流程之间的差距，将关注点从表面流畅度转向更深层的语义和语境忠实度。

> We present MAATS, a Multi Agent Automated Translation System that leverages the Multidimensional Quality Metrics (MQM) framework as a fine-grained signal for error detection and refinement. MAATS employs multiple specialized AI agents, each focused on a distinct MQM category (e.g., Accuracy, Fluency, Style, Terminology), followed by a synthesis agent that integrates the annotations to iteratively refine translations. This design contrasts with conventional single-agent methods that rely on self-correction.
  Evaluated across diverse language pairs and Large Language Models (LLMs), MAATS outperforms zero-shot and single-agent baselines with statistically significant gains in both automatic metrics and human assessments. It excels particularly in semantic accuracy, locale adaptation, and linguistically distant language pairs. Qualitative analysis highlights its strengths in multi-layered error diagnosis, omission detection across perspectives, and context-aware refinement. By aligning modular agent roles with interpretable MQM dimensions, MAATS narrows the gap between black-box LLMs and human translation workflows, shifting focus from surface fluency to deeper semantic and contextual fidelity.

[Arxiv](https://arxiv.org/abs/2505.14848)