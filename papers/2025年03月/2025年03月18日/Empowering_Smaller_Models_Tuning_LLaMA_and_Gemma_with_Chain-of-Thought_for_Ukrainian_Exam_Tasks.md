# 赋能小型模型：使用思维链方法微调 LLaMA 和 Gemma 解决乌克兰考试任务

发布时间：2025年03月18日

`LLM应用` `教育技术`

> Empowering Smaller Models: Tuning LLaMA and Gemma with Chain-of-Thought for Ukrainian Exam Tasks

# 摘要

> 领先的大型语言模型在推理密集型任务中表现优异，例如标准化教育测试。然而，在基础设施受限的环境中，它们往往需要大量训练。尽管小型或紧凑型模型更高效，但它们在支持代表性不足的语言方面仍有欠缺，导致关键领域性能不足。本研究探讨了对紧凑型开放权重语言模型进行参数高效微调，以处理乌克兰语中的推理密集型任务，基于ZNO-Eval基准的发现。通过对LLaMA 3.1（80亿参数）、LLaMA 3.2（30亿参数）和Gemma 2（90亿参数）模型进行链式思考解决方案的参数高效微调，在复杂匹配任务中相比仅对答案字母微调，测试分数提升了17.4%，整体提升1.6%，同时增强了可解释性和鲁棒性。此外，结合任务主题和逐步解决方案生成的微调方法在匹配任务中优于标准链式思考微调，由于引导模型回忆和应用领域相关知识，比最佳LLaMA 3.2模型提升了5.4%。与Qwen、DeepSeek R1、OpenAI o1和o3、Gemini和Claude等领先开放权重和专有模型的零样本评估结果对比，表明使用2,032个逐步解决方案和20到5000万可训练参数，在单个A100 GPU上对LLaMA和Gemma模型进行微调，使其能够超越GPT-4o mini、Mistral Large和更大的开放权重模型。本研究还评估了量化适配器与基础模型合并对生成质量的影响。源代码和微调后的模型可在https://github.com/NLPForUA/ZNO获取。

> Leading large language models have demonstrated impressive capabilities in reasoning-intensive tasks, such as standardized educational testing. However, they often require extensive training in low-resource settings with inaccessible infrastructure. Small or compact models, though more efficient, frequently lack sufficient support for underrepresented languages, leaving a performance gap in critical domains. This work explores the potential of parameter-efficient fine-tuning of compact open-weight language models to handle reasoning-intensive tasks in the underrepresented Ukrainian language, building on the findings of the ZNO-Eval benchmark. Parameter-efficient fine-tuning of LLaMA 3.1 (8 billion parameters), LLaMA 3.2 (3 billion parameters), and Gemma 2 (9 billion parameters) models on chain-of-thought solutions resulted in a modest test score improvement of up to 17.4% on complex matching tasks and 1.6% overall compared to tuning on answer letters alone, offering enhanced interpretability and robustness. In addition, the proposed tuning method with joint task topic and step-by-step solution generation outperforms standard chain-of-thought tuning in matching tasks and provides a 5.4% gain over the best LLaMA 3.2 model due to guiding the model to recall and apply domain-relevant information. Contrasting obtained results with zero-shot evaluations of leading open-weight and proprietary models such as Qwen, DeepSeek R1, OpenAI o1 and o3, Gemini, and Claude, highlight that fine-tuning LLaMA and Gemma models with 2,032 step-by-step solutions and 20 to 50 million trainable parameters on a single A100 GPU lets them outperform GPT-4o mini, Mistral Large, and larger open-weight models. This research also evaluates how merging the quantized adapter with the base model influences the generation quality. Source code and tuned models are available at https://github.com/NLPForUA/ZNO.

[Arxiv](https://arxiv.org/abs/2503.13988)