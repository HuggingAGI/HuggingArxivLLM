# Top-H解码：基于有界熵的文本生成创造性与连贯性适配

发布时间：2025年09月02日

`LLM理论` `媒体与娱乐`

> Top-H Decoding: Adapting the Creativity and Coherence with Bounded Entropy in Text Generation

# 摘要

> 大型语言模型（LLMs）虽在各类任务中表现惊艳，但在开放式文本生成中常陷入两难：如何在激发多样性与创造力的同时，确保逻辑连贯性。现有截断采样技术（如温度缩放、top-【数学公式】（核）采样、min-【数学公式】采样）都试图平衡这一矛盾，却均存在局限——尤其未能将模型的置信度有效融入采样策略。例如，min-【数学公式】采样仅以单个最高概率token作为置信度的启发式依据，导致概率分布信息未被充分利用。

为破解模型置信度整合难题，本文提出**top-H**解码方法。我们首先构建**熵约束最小散度**问题，为截断采样中创造力与连贯性的相互作用奠定理论基础；接着证明此最小化问题等价于**熵约束质量最大化**（ECMM）问题，且该问题为NP难；最终提出top-H解码——一种计算高效的贪心算法，以求解ECMM问题。

大量实证结果显示：在创意写作基准测试中，top-H性能超越当前最优（SoTA）的min-【数学公式】采样，提升幅度最高达**25.63%**；同时在GPQA、GSM8K、MT-Bench等问答数据集上，仍能保持良好的稳健性。此外，“LLM作为评判者”的评估进一步验证：即便在创造力至关重要的高温度设置下，top-H生成的文本依然连贯。

综上，top-H刷新了开放式文本生成的技术上限（SoTA），且能*轻松集成*至各类创意写作应用。代码已开源，地址为https://github.com/ErfanBaghaei/Top-H-Decoding。

> Large language models (LLMs), despite their impressive performance across a wide range of tasks, often struggle to balance two competing objectives in open-ended text generation: fostering diversity and creativity while preserving logical coherence. Existing truncated sampling techniques, including temperature scaling, top-\$p\$ (nucleus) sampling, and min-\$p\$ sampling, aim to manage this trade-off. However, they exhibit limitations, particularly in the effective incorporation of the confidence of the model into the corresponding sampling strategy. For example, min-\$p\$ sampling relies on a single top token as a heuristic for confidence, eventually underutilizing the information of the probability distribution. Toward effective incorporation of the confidence of the model, in this paper, we present **top-H** decoding. We first establish the theoretical foundation of the interplay between creativity and coherence in truncated sampling by formulating an **entropy-constrained minimum divergence** problem. We then prove this minimization problem to be equivalent to an **entropy-constrained mass maximization** (ECMM) problem, which is NP-hard. Finally, we present top-H decoding, a computationally efficient greedy algorithm to solve the ECMM problem. Extensive empirical evaluations demonstrate that top-H outperforms the state-of-the-art (SoTA) alternative of min-\$p\$ sampling by up to **25.63%** on creative writing benchmarks, while maintaining robustness on question-answering datasets such as GPQA, GSM8K, and MT-Bench. Additionally, an *LLM-as-judge* evaluation confirms that top-H indeed produces coherent outputs even at higher temperatures, where creativity is especially critical. In summary, top-H advances SoTA in open-ended text generation and can be *easily integrated* into creative writing applications. The code is available at https://github.com/ErfanBaghaei/Top-H-Decoding.

[Arxiv](https://arxiv.org/abs/2509.02510)