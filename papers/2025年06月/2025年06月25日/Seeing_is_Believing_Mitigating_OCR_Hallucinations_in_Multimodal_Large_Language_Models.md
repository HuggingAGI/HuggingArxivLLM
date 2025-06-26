# # 所见即所信？多模态大模型中的OCR幻觉缓解之道

发布时间：2025年06月25日

`LLM应用` `文档处理` `计算机视觉`

> Seeing is Believing? Mitigating OCR Hallucinations in Multimodal Large Language Models

# 摘要

> 多模态大语言模型的最新进展通过融合文本与视觉信息显著提升了文档理解能力。然而，在现实场景中，尤其是面对视觉降级的情况，现有模型的局限性逐渐显现。在这些情况下，当前的响应机制往往难以准确捕捉视觉降级和模糊性，容易过度依赖语言先验或产生偏离实际的视觉-文本推理。这种对不确定性的识别困难常导致幻觉内容的生成，特别是在无法提供准确答案时。为了深入研究和剖析这一现象及其挑战，我们推出了KIE-HVQA，这是首个专注于评估降级文档理解中OCR幻觉的基准测试。该数据集涵盖身份证明和发票等多种测试样本，并模拟了现实世界中的降级场景以测试OCR的可靠性。这一设计使我们能够评估模型在输入降级情况下区分可靠视觉信息并作出恰当回应的能力，从而凸显了在处理不确定数据时避免产生幻觉的重要性。为了实现视觉忠实推理并解决上述问题，我们提出了一种基于GRPO的创新框架，其中包含了独特的奖励机制。通过在监督微调和强化学习框架中引入对视觉不确定性的自我感知能力，并采用拒绝回答的策略来增加任务难度，我们成功地缓解了模糊区域的幻觉问题。在Qwen2.5-VL上的实验结果表明，我们的7B参数模型在KIE-HVQA基准测试中实现了相比GPT-4o 22%的绝对无幻觉准确率提升，且在标准任务上表现稳定，充分证明了其有效性和鲁棒性。

> Recent advancements in multimodal large language models have enhanced document understanding by integrating textual and visual information. However, existing models exhibit incompleteness within their paradigm in real-world scenarios, particularly under visual degradation. In such conditions, the current response paradigm often fails to adequately perceive visual degradation and ambiguity, leading to overreliance on linguistic priors or misaligned visual-textual reasoning. This difficulty in recognizing uncertainty frequently results in the generation of hallucinatory content, especially when a precise answer is not feasible. To better demonstrate and analyze this phenomenon and problem, we propose KIE-HVQA, the first benchmark dedicated to evaluating OCR hallucination in degraded document understanding. This dataset includes test samples spanning identity cards and invoices, with simulated real-world degradations for OCR reliability. This setup allows for evaluating models' capacity, under degraded input, to distinguish reliable visual information and answer accordingly, thereby highlighting the challenge of avoiding hallucination on uncertain data. To achieve vision-faithful reasoning and thereby avoid the aforementioned issues, we further introduce a GRPO-based framework featuring a novel reward mechanism. By incorporating a self-awareness of visual uncertainty and an analysis method that initiates refusal to answer to increase task difficulty within our supervised fine-tuning and reinforcement learning framework, we successfully mitigated hallucinations in ambiguous regions. Experiments on Qwen2.5-VL demonstrate that our 7B-parameter model achieves a 22\% absolute improvement in hallucination-free accuracy over GPT-4o on KIE-HVQA and there is no significant performance drop in standard tasks, highlighting both effectiveness and robustness.

[Arxiv](https://arxiv.org/abs/2506.20168)