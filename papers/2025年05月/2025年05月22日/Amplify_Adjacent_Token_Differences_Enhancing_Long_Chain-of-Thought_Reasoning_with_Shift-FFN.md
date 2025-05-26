# 增强相邻标记差异：利用 Shift-FFN 提升长链式推理能力

发布时间：2025年05月22日

`LLM应用` `数学推理` `人工智能教育`

> Amplify Adjacent Token Differences: Enhancing Long Chain-of-Thought Reasoning with Shift-FFN

# 摘要

> 最近，OpenAI-o1 和 DeepSeek-R1 等模型通过长链式思考（Long-CoT）推理在复杂推理任务中展现了卓越的性能。尽管将这种能力蒸馏到学生模型中能显著提升其表现，但本研究发现，使用完整参数或低秩LoRA对长CoT数据进行微调，常常导致循环推理，即模型不断重复之前的推理步骤，直到达到最大长度限制。进一步分析表明，相邻标记之间的表示差异越小，模型就越容易陷入循环推理。为解决这一问题，本研究提出了一种名为移位前馈网络（Shift-FFN）的新方法，该方法通过在将当前标记输入前馈网络（FFN）之前，将其表示与前一个标记的表示进行编辑，从而动态放大相邻标记之间的表示差异。在多个数学推理任务上的广泛实验表明，与完整的微调和标准LoRA相比，结合了Shift-FFN的LoRA在不同数据规模下均能实现更高的准确性和更低的循环推理率。我们的数据和代码可在 https://anonymous.4open.science/r/Shift-FFN 获取。


> Recently, models such as OpenAI-o1 and DeepSeek-R1 have demonstrated remarkable performance on complex reasoning tasks through Long Chain-of-Thought (Long-CoT) reasoning. Although distilling this capability into student models significantly enhances their performance, this paper finds that fine-tuning LLMs with full parameters or LoRA with a low rank on long CoT data often leads to Cyclical Reasoning, where models repeatedly reiterate previous inference steps until the maximum length limit. Further analysis reveals that smaller differences in representations between adjacent tokens correlates with a higher tendency toward Cyclical Reasoning. To mitigate this issue, this paper proposes Shift Feedforward Networks (Shift-FFN), a novel approach that edits the current token's representation with the previous one before inputting it to FFN. This architecture dynamically amplifies the representation differences between adjacent tokens. Extensive experiments on multiple mathematical reasoning tasks demonstrate that LoRA combined with Shift-FFN achieves higher accuracy and a lower rate of Cyclical Reasoning across various data sizes compared to full fine-tuning and standard LoRA. Our data and code are available at https://anonymous.4open.science/r/Shift-FFN

[Arxiv](https://arxiv.org/abs/2505.17153)