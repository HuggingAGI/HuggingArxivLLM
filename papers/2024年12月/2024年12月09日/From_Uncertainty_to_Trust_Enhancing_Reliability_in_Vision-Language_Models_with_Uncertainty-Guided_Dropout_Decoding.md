# 从不确定性走向信任：借助不确定性引导的 Dropout 解码增强视觉语言模型的可靠性

发布时间：2024年12月09日

`LLM应用` `多模态`

> From Uncertainty to Trust: Enhancing Reliability in Vision-Language Models with Uncertainty-Guided Dropout Decoding

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务中能力出众，但易误解视觉输入，常产生幻觉和不可靠的输出。为解决这些难题，我们提出了Dropout Decoding，这是一种全新的推理时方法，能量化视觉标记的不确定性，并选择性地遮蔽不确定标记以优化解码。我们的方法把每个视觉标记投射到文本空间，分解为偶然和认知成分来衡量其不确定性。具体来说，我们着重于认知不确定性，它能更有效地捕捉与感知相关的错误。受Dropout正则化的启发，我们引入不确定性引导的标记Dropout，将Dropout原则应用于输入的视觉标记而非模型参数，且在推理而非训练时使用。通过聚合来自一组掩码解码上下文的预测，Dropout Decoding 有效地减轻了因视觉标记误解导致的错误。在CHAIR、THRONE和MMBench等基准测试中的评估显示，Dropout Decoding 显著减少了对象幻觉（OH），并在各种视觉情境中提升了LVLM输出的可靠性和质量。

> Large vision-language models (LVLMs) demonstrate remarkable capabilities in multimodal tasks but are prone to misinterpreting visual inputs, often resulting in hallucinations and unreliable outputs. To address these challenges, we propose Dropout Decoding, a novel inference-time approach that quantifies the uncertainty of visual tokens and selectively masks uncertain tokens to improve decoding. Our method measures the uncertainty of each visual token by projecting it onto the text space and decomposing it into aleatoric and epistemic components. Specifically, we focus on epistemic uncertainty, which captures perception-related errors more effectively. Inspired by dropout regularization, we introduce uncertainty-guided token dropout, which applies the dropout principle to input visual tokens instead of model parameters, and during inference rather than training. By aggregating predictions from an ensemble of masked decoding contexts, Dropout Decoding robustly mitigates errors arising from visual token misinterpretations. Evaluations on benchmarks including CHAIR, THRONE, and MMBench demonstrate that Dropout Decoding significantly reduces object hallucinations (OH) and enhances both reliability and quality of LVLM outputs across diverse visual contexts.

[Arxiv](https://arxiv.org/abs/2412.06474)