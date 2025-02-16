# CodeSteer：借助代码与文本引导的符号增强语言模型

发布时间：2025年02月04日

`LLM应用

摘要中的论文主要探讨了如何优化和指导大型语言模型在代码生成和文本推理之间的切换，通过构建基准测试和数据集，提出了一种新的方法CodeSteer，并展示了其在提升模型性能方面的有效性。这表明研究集中在模型的应用和性能提升上，属于LLM应用类别。` `软件工程` `人工智能`

> CodeSteer: Symbolic-Augmented Language Models via Code/Text Guidance

# 摘要

> 现有方法未能有效引导大型语言模型 (LLMs) 在文本推理与代码生成之间切换，导致其符号计算能力未得到充分利用。为此，我们提出 CodeSteer，一种有效指导 LLM 进行代码/文本生成的方法。我们构建了包含 37 个可调节复杂度符号任务的综合性基准测试 SymBench，并合成了 12,000 个包含多轮引导/生成轨迹和 5,500 个引导对比对的数据集。通过全新设计的多轮监督微调 (SFT) 和直接偏好优化 (DPO) 对 Llama-3-8B 模型进行微调，最终得到 CodeSteerLLM 模型。该模型结合了我们提出的符号和自答检查器，能够有效引导更大模型的代码/文本生成。将 CodeSteer 应用于 GPT-4o，使其平均性能得分从 53.3 提升至 86.4，超越了现有最佳 LLM（包括 OpenAI o1 (82.7)、o1-preview (74.8) 和 DeepSeek R1 (76.8)）在所有 37 个任务中的表现（28 个已知，9 个未知）。针对 GPT-4o 进行训练的 CodeSteer 展现出卓越的泛化能力，在 Claude、Mistral 和 GPT-3.5 上平均提升了 41.8 的性能。CodeSteer 指导的 LLMs 充分利用符号计算，在高度复杂的任务中保持强劲性能。模型、数据集和代码可在 https://github.com/yongchao98/CodeSteer-v1.0 获取。

> Existing methods fail to effectively steer Large Language Models (LLMs) between textual reasoning and code generation, leaving symbolic computing capabilities underutilized. We introduce CodeSteer, an effective method for guiding LLM code/text generation. We construct a comprehensive benchmark SymBench comprising 37 symbolic tasks with adjustable complexity and also synthesize datasets of 12k multi-round guidance/generation trajectories and 5.5k guidance comparison pairs. We fine-tune the Llama-3-8B model with a newly designed multi-round supervised fine-tuning (SFT) and direct preference optimization (DPO). The resulting model, CodeSteerLLM, augmented with the proposed symbolic and self-answer checkers, effectively guides the code/text generation of larger models. Augmenting GPT-4o with CodeSteer raises its average performance score from 53.3 to 86.4, even outperforming the existing best LLM OpenAI o1 (82.7), o1-preview (74.8), and DeepSeek R1 (76.8) across all 37 tasks (28 seen, 9 unseen). Trained for GPT-4o, CodeSteer demonstrates superior generalizability, providing an average 41.8 performance boost on Claude, Mistral, and GPT-3.5. CodeSteer-guided LLMs fully harness symbolic computing to maintain strong performance on highly complex tasks. Models, Datasets, and Codes are available at https://github.com/yongchao98/CodeSteer-v1.0.

[Arxiv](https://arxiv.org/abs/2502.04350)