# 拨开3D视觉语言理解的迷雾：以对象为中心的评估通过分析链

发布时间：2025年03月28日

`其他

理由：这篇论文主要讨论的是三维视觉语言（3D-VL）模型的评估基准测试的不足，并提出了一种新的基准测试Beacon3D。虽然提到了大型语言模型（LLMs）与3D-VL模型的结合，但其主要贡献在于评估方法和基准测试的设计，而非直接探讨LLMs的应用或理论。因此，这篇论文更适合归类为“其他”。` `计算机视觉` `三维视觉`

> Unveiling the Mist over 3D Vision-Language Understanding: Object-centric Evaluation with Chain-of-Analysis

# 摘要

> 现有的三维视觉语言（3D-VL）基准测试在评估模型能力时存在明显不足，如同一层迷雾遮蔽了我们对模型能力及任务理解的深入洞察。这层迷雾的成因主要源于三大关键限制：首先是测试数据的缺陷，例如在定位任务中使用模糊的参考文本，导致测试结果出现偏差；其次是过于简化的评估指标，如对问答（QA）对的准确性进行简单平均，无法全面反映模型的真实能力；最后是现有基准测试将定位与问答任务割裂开来，忽视了两者之间的内在连贯性。

为了解决这一问题，我们提出了Beacon3D——一个专注于3D-VL定位与问答任务的新基准测试，为评估3D-VL理解提供了全新视角。Beacon3D具有三大特色：(i) 高质量的测试数据，语言精准且自然；(ii) 以物体为中心的评估方式，通过多次测试同一物体确保评估的稳健性；(iii) 一种全新的分析链范式，旨在解决语言稳健性问题，并在定位与问答任务之间实现模型性能的连贯性。

我们在Beacon3D上对现有先进的3D-VL模型进行了全面评估，发现：(i) 以物体为中心的评估揭示了模型的真实性能，尤其是在问答任务中的泛化能力较弱；(ii) 定位与问答之间的连贯性在当前3D-VL模型中仍然十分脆弱；(iii) 尽管将大型语言模型（LLMs）与3D-VL模型结合是一种常见做法，但它会削弱定位能力，且尚未显著提升问答能力。我们希望Beacon3D及我们的分析能够为3D-VL领域的发展提供有益的指导。

> Existing 3D vision-language (3D-VL) benchmarks fall short in evaluating 3D-VL models, creating a "mist" that obscures rigorous insights into model capabilities and 3D-VL tasks. This mist persists due to three key limitations. First, flawed test data, like ambiguous referential text in the grounding task, can yield incorrect and unreliable test results. Second, oversimplified metrics such as simply averaging accuracy per question answering (QA) pair, cannot reveal true model capability due to their vulnerability to language variations. Third, existing benchmarks isolate the grounding and QA tasks, disregarding the underlying coherence that QA should be based on solid grounding capabilities. To unveil the "mist", we propose Beacon3D, a benchmark for 3D-VL grounding and QA tasks, delivering a perspective shift in the evaluation of 3D-VL understanding. Beacon3D features (i) high-quality test data with precise and natural language, (ii) object-centric evaluation with multiple tests per object to ensure robustness, and (iii) a novel chain-of-analysis paradigm to address language robustness and model performance coherence across grounding and QA. Our evaluation of state-of-the-art 3D-VL models on Beacon3D reveals that (i) object-centric evaluation elicits true model performance and particularly weak generalization in QA; (ii) grounding-QA coherence remains fragile in current 3D-VL models, and (iii) incorporating large language models (LLMs) to 3D-VL models, though as a prevalent practice, hinders grounding capabilities and has yet to elevate QA capabilities. We hope Beacon3D and our comprehensive analysis could benefit the 3D-VL community towards faithful developments.

[Arxiv](https://arxiv.org/abs/2503.22420)