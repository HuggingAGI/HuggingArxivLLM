# Med-RewardBench：医疗多模态大型语言模型的奖励模型与评判模型基准测试

发布时间：2025年08月29日

`LLM应用` `医疗健康`

> Med-RewardBench: Benchmarking Reward Models and Judges for Medical Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在医疗领域应用前景广阔，可助力疾病诊断、临床决策等关键任务。但这类任务对响应的准确性、语境适应性和专业契合度要求极高，因此可靠的奖励模型与评判器成为关键。尽管至关重要，医疗奖励模型（MRMs）与评判器的研究却严重滞后，至今缺乏专门针对临床需求的评估基准。现有基准要么聚焦通用MLLM能力，要么将模型视为求解器进行评测，却忽略了诊断准确性、临床相关性等核心评估维度。为此，我们提出Med-RewardBench——首个专为评估医疗场景下MRMs与评判器设计的基准。Med-RewardBench的核心是一个多模态数据集，覆盖13个器官系统、8个临床科室，包含1026例专家标注病例。我们通过严格的三步流程，确保了六个临床关键维度评估数据的高质量。我们对32个当前最先进的MLLMs（包括开源、专有及医疗专用模型）进行了评估，结果显示模型输出与专家判断的一致性仍面临巨大挑战。此外，我们还构建了基线模型，经微调后性能显著提升。

> Multimodal large language models (MLLMs) hold significant potential in medical applications, including disease diagnosis and clinical decision-making. However, these tasks require highly accurate, context-sensitive, and professionally aligned responses, making reliable reward models and judges critical. Despite their importance, medical reward models (MRMs) and judges remain underexplored, with no dedicated benchmarks addressing clinical requirements. Existing benchmarks focus on general MLLM capabilities or evaluate models as solvers, neglecting essential evaluation dimensions like diagnostic accuracy and clinical relevance. To address this, we introduce Med-RewardBench, the first benchmark specifically designed to evaluate MRMs and judges in medical scenarios. Med-RewardBench features a multimodal dataset spanning 13 organ systems and 8 clinical departments, with 1,026 expert-annotated cases. A rigorous three-step process ensures high-quality evaluation data across six clinically critical dimensions. We evaluate 32 state-of-the-art MLLMs, including open-source, proprietary, and medical-specific models, revealing substantial challenges in aligning outputs with expert judgment. Additionally, we develop baseline models that demonstrate substantial performance improvements through fine-tuning.

[Arxiv](https://arxiv.org/abs/2508.21430)