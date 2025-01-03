# 动态注意力引导的上下文解码：减轻大型语言模型中的上下文忠实性幻觉

发布时间：2025年01月02日

`LLM应用

**理由**：该论文主要关注如何通过改进解码机制（动态注意力引导的上下文解码，DAGCD）来提升大型语言模型（LLMs）在问答任务中的忠实性和鲁棒性。这属于对LLM在实际应用中的优化和改进，因此归类为LLM应用。` `问答系统`

> Dynamic Attention-Guided Context Decoding for Mitigating Context Faithfulness Hallucinations in Large Language Models

# 摘要

> 大型语言模型（LLMs）常因上下文利用不足和高输出不确定性而出现上下文忠实性幻觉，导致输出偏离检索信息。我们的实验表明，高不确定性与幻觉密切相关。我们推测注意力机制编码了上下文利用的信号，并通过探测分析验证了这一假设。基于此，我们提出了动态注意力引导的上下文解码（DAGCD），这是一个轻量级框架，将注意力分布和不确定性信号整合到单次解码中。问答数据集上的实验显示，DAGCD在保持计算效率的同时，显著提升了忠实性和鲁棒性。

> Large language models (LLMs) often suffer from context faithfulness hallucinations, where outputs deviate from retrieved information due to insufficient context utilization and high output uncertainty. Our uncertainty evaluation experiments reveal a strong correlation between high uncertainty and hallucinations. We hypothesize that attention mechanisms encode signals indicative of contextual utilization, validated through probing analysis. Based on these insights, we propose Dynamic Attention-Guided Context Decoding (DAGCD), a lightweight framework that integrates attention distributions and uncertainty signals in a single-pass decoding process. Experiments across QA datasets demonstrate DAGCD's effectiveness, achieving significant improvements in faithfulness and robustness while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2501.01059)