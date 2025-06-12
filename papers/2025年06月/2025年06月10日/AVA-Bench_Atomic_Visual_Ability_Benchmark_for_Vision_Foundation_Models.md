# AVA-Bench：专为视觉基础模型设计的原子级视觉能力评测基准

发布时间：2025年06月10日

`其他` `计算机视觉` `视觉推理`

> AVA-Bench: Atomic Visual Ability Benchmark for Vision Foundation Models

# 摘要

> 视觉基础模型（VFMs）的崛起促使了系统性评估的需求。常见的做法是将VFMs与大型语言模型（LLMs）搭配，作为通用任务的处理模块，随后在广泛的视觉问答（VQA）基准上进行评估。然而，这一方法存在两个关键盲点：(i) 指令微调数据可能与VQA测试分布不匹配，这意味着错误预测可能源于数据不匹配，而非VFM的视觉不足；(ii) VQA基准通常需要多种视觉能力，难以分辨错误是源于缺乏所有必需能力，还是仅缺少某一个关键能力。为解决这些问题，我们引入了AVA-Bench，这是首个明确分解14种原子视觉能力（AVAs）的基准——如定位、深度估计和空间理解等基础技能，这些技能共同支持复杂的视觉推理任务。通过分离AVAs并在每项能力上匹配训练和测试分布，AVA-Bench能够精准识别VFM的优势与不足。将AVA-Bench应用于领先的VFMs，揭示了独特的"能力指纹"，将VFM选择从经验猜测转变为基于原则的工程实践。值得注意的是，我们发现0.5B参数量的LLM与7B参数量的LLM在VFM排名上相似，但GPU算力消耗减少了8倍，从而实现了更高效的评估。通过提供全面且透明的基准，我们希望AVA-Bench为下一代VFMs奠定基础。


> The rise of vision foundation models (VFMs) calls for systematic evaluation. A common approach pairs VFMs with large language models (LLMs) as general-purpose heads, followed by evaluation on broad Visual Question Answering (VQA) benchmarks. However, this protocol has two key blind spots: (i) the instruction tuning data may not align with VQA test distributions, meaning a wrong prediction can stem from such data mismatch rather than a VFM' visual shortcomings; (ii) VQA benchmarks often require multiple visual abilities, making it hard to tell whether errors stem from lacking all required abilities or just a single critical one. To address these gaps, we introduce AVA-Bench, the first benchmark that explicitly disentangles 14 Atomic Visual Abilities (AVAs) -- foundational skills like localization, depth estimation, and spatial understanding that collectively support complex visual reasoning tasks. By decoupling AVAs and matching training and test distributions within each, AVA-Bench pinpoints exactly where a VFM excels or falters. Applying AVA-Bench to leading VFMs thus reveals distinctive "ability fingerprints," turning VFM selection from educated guesswork into principled engineering. Notably, we find that a 0.5B LLM yields similar VFM rankings as a 7B LLM while cutting GPU hours by 8x, enabling more efficient evaluation. By offering a comprehensive and transparent benchmark, we hope AVA-Bench lays the foundation for the next generation of VFMs.

[Arxiv](https://arxiv.org/abs/2506.09082)