# R1-Code-Interpreter: 结合监督学习与强化学习，赋能 LLMs 实现代码推理能力

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了如何通过代码生成和推理来提升大型语言模型在复杂任务中的表现，属于LLM的应用层面研究。` `人工智能` `代码生成`

> R1-Code-Interpreter: Training LLMs to Reason with Code via Supervised and Reinforcement Learning

# 摘要

> 尽管R1类模型在推理和规划方面取得了进展，大型语言模型（LLMs）在需要精确计算、符号操作、优化和算法推理的任务中仍然表现挣扎，因为文本推理缺乏代码执行的严谨性。一个关键挑战是让LLMs能够决定何时使用文本推理，何时使用代码生成。虽然OpenAI训练模型在需要时调用代码解释器，但公开研究缺乏关于如何对预训练LLMs进行对齐以有效利用代码并在多样化任务中进行泛化的指导。

我们提出了R1-Code-Interpreter，这是一个通过多轮监督微调（SFT）和强化学习（RL）训练的纯文本LLM的扩展，能够在逐步推理过程中自主生成多个代码查询。我们整理了144个推理和规划任务（107个用于训练，37个用于测试），每个任务包含超过200个多样化的问题。我们使用各种SFT和RL策略微调Qwen-2.5模型（3B/7B/14B），研究不同的答案格式、推理与非推理模型、冷启动与热启动、GRPO与PPO，以及屏蔽与非屏蔽代码输出。

与之前的窄领域RL工作不同，我们发现代码解释器的训练难度显著增加，原因在于任务多样性和昂贵的代码执行成本，这凸显了SFT阶段的关键作用。我们的最终模型R1-CI-14B在37个测试任务上的平均准确率从44.0%提升至64.1%，优于纯文本GPT-4o（58.6%），并接近配备代码解释器的GPT-4o（70.9%），同时通过代码生成出现了自我检查的行为。

数据集、代码和模型可在https://github.com/yongchao98/R1-Code-Interpreter和https://huggingface.co/yongchao98获取。

> Despite advances in reasoning and planning of R1-like models, Large Language Models (LLMs) still struggle with tasks requiring precise computation, symbolic manipulation, optimization, and algorithmic reasoning, in which textual reasoning lacks the rigor of code execution. A key challenge is enabling LLMs to decide when to use textual reasoning versus code generation. While OpenAI trains models to invoke a Code Interpreter as needed, public research lacks guidance on aligning pre-trained LLMs to effectively leverage code and generalize across diverse tasks. We present R1-Code-Interpreter, an extension of a text-only LLM trained via multi-turn supervised fine-tuning (SFT) and reinforcement learning (RL) to autonomously generate multiple code queries during step-by-step reasoning. We curate 144 reasoning and planning tasks (107 for training, 37 for testing), each with over 200 diverse questions. We fine-tune Qwen-2.5 models (3B/7B/14B) using various SFT and RL strategies, investigating different answer formats, reasoning vs. non-reasoning models, cold vs. warm starts, GRPO vs. PPO, and masked vs. unmasked code outputs. Unlike prior RL work on narrow domains, we find that Code Interpreter training is significantly harder due to high task diversity and expensive code execution, highlighting the critical role of the SFT stage. Our final model, R1-CI-14B, improves average accuracy on the 37 test tasks from 44.0\% to 64.1\%, outperforming GPT-4o (text-only: 58.6\%) and approaching GPT-4o with Code Interpreter (70.9\%), with the emergent self-checking behavior via code generation. Datasets, Codes, and Models are available at https://github.com/yongchao98/R1-Code-Interpreter and https://huggingface.co/yongchao98.

[Arxiv](https://arxiv.org/abs/2505.21668)