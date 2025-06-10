# # SAP-Bench: 多模态大型语言模型在手术计划中的基准测试
SAP-Bench 是一个多模态大型语言模型（MLLMs）在手术行动规划任务中的基准测试框架，旨在评估这些模型在复杂外科手术场景中的理解和规划能力。

发布时间：2025年06月08日

`LLM应用` `知识图谱`

> SAP-Bench: Benchmarking Multimodal Large Language Models in Surgical Action Planning

# 摘要

> 有效的评估对于推动多模态大型语言模型（MLLM）研究的进步至关重要。手术动作规划（SAP）任务旨在从视觉输入中生成未来的动作序列，这需要精确和复杂的分析能力。与数学推理不同，手术决策是在生命攸关的领域中进行的，需要细致且可验证的过程来确保可靠性和患者安全。该任务要求能够区分原子视觉动作并协调复杂且长期的程序，而这些能力是当前基准测试未能充分评估的。

为了解决这一差距，我们引入了SAP-Bench，这是一个大规模、高质量的数据集，旨在使多模态大型语言模型（MLLMs）能够执行可解释的手术动作规划。我们的SAP-Bench基准源自胆囊切除术程序的上下文，平均时长为1137.5秒，并引入了基于时间的手术动作注释，包括1226个经过临床验证的动作片段（平均时长：68.7秒），涵盖了74种程序中的五种基本手术动作。该数据集提供了1152个战略性采样的当前帧，每个帧都与相应的下一步动作配对，作为多模态分析的锚点。

我们提出了MLLM-SAP框架，该框架利用MLLMs根据当前手术场景和自然语言指令生成下一步动作建议，并通过注入手术领域知识来增强模型性能。为了评估我们的数据集的有效性以及当前模型的更广泛能力，我们评估了七种最先进的MLLM（例如，OpenAI-o1、GPT-4o、QwenVL2.5-72B、Claude-3.5-Sonnet、GeminiPro2.5、Step-1o 和 GLM-4v），并揭示了在下一步动作预测性能方面的关键差距。

> Effective evaluation is critical for driving advancements in MLLM research. The surgical action planning (SAP) task, which aims to generate future action sequences from visual inputs, demands precise and sophisticated analytical capabilities. Unlike mathematical reasoning, surgical decision-making operates in life-critical domains and requires meticulous, verifiable processes to ensure reliability and patient safety. This task demands the ability to distinguish between atomic visual actions and coordinate complex, long-horizon procedures, capabilities that are inadequately evaluated by current benchmarks. To address this gap, we introduce SAP-Bench, a large-scale, high-quality dataset designed to enable multimodal large language models (MLLMs) to perform interpretable surgical action planning. Our SAP-Bench benchmark, derived from the cholecystectomy procedures context with the mean duration of 1137.5s, and introduces temporally-grounded surgical action annotations, comprising the 1,226 clinically validated action clips (mean duration: 68.7s) capturing five fundamental surgical actions across 74 procedures. The dataset provides 1,152 strategically sampled current frames, each paired with the corresponding next action as multimodal analysis anchors. We propose the MLLM-SAP framework that leverages MLLMs to generate next action recommendations from the current surgical scene and natural language instructions, enhanced with injected surgical domain knowledge. To assess our dataset's effectiveness and the broader capabilities of current models, we evaluate seven state-of-the-art MLLMs (e.g., OpenAI-o1, GPT-4o, QwenVL2.5-72B, Claude-3.5-Sonnet, GeminiPro2.5, Step-1o, and GLM-4v) and reveal critical gaps in next action prediction performance.

[Arxiv](https://arxiv.org/abs/2506.07196)