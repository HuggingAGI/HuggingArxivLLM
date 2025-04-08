# LLM评估人员偏爱自己是否事出有因？

发布时间：2025年04月04日

`LLM理论` `人工智能`

> Do LLM Evaluators Prefer Themselves for a Reason?

# 摘要

> 大型语言模型（LLMs）正越来越多地被用作自动评估器，广泛应用于基准测试、奖励建模和自我改进等领域。先前研究表明，LLMs可能存在自我偏好偏差，即倾向于偏好自己的生成结果，且这种倾向往往随模型规模和能力的提升而增强。这引发了一个关键问题：自我偏好是不利的，还是仅仅反映了更强大模型生成的客观上更优质的输出？由于以往研究多依赖主观任务，解开这两者之间的关系颇具挑战性。

为解决这一问题，我们采用可验证的基准测试（如数学推理、事实知识、代码生成）来研究自我偏好，这些基准测试支持客观的地面真实评估。这使我们能够区分有害的自我偏好（偏好客观上较差的响应）与合法的自我偏好（偏好真正更优质的响应）。我们在控制的评估条件下，对包括Llama、Qwen、Gemma、Mistral、Phi、GPT、DeepSeek在内的多种模型家族进行了大规模实验。

研究结果揭示了三个关键发现：
1. 更好的生成器是更好的评判者——LLM评估器的准确性与其任务性能密切相关，且有能力模型中的大部分自我偏好是合法的。
2. 有害的自我偏好仍然存在，尤其是在评估器模型在特定任务实例上作为生成器表现不佳时。更强的模型在出错时表现出更明显的有害偏差，尽管这种错误生成的频率较低。
3. 推理时的缩放策略，例如在评估前生成一个长的思维链，能够有效减少有害的自我偏好。

这些结果为我们理解基于LLM的评估提供了更细致的视角，并为提升其可靠性提供了实用的见解。

> Large language models (LLMs) are increasingly used as automatic evaluators in applications such as benchmarking, reward modeling, and self-refinement. Prior work highlights a potential self-preference bias where LLMs favor their own generated responses, a tendency often intensifying with model size and capability. This raises a critical question: Is self-preference detrimental, or does it simply reflect objectively superior outputs from more capable models? Disentangling these has been challenging due to the usage of subjective tasks in previous studies. To address this, we investigate self-preference using verifiable benchmarks (mathematical reasoning, factual knowledge, code generation) that allow objective ground-truth assessment. This enables us to distinguish harmful self-preference (favoring objectively worse responses) from legitimate self-preference (favoring genuinely superior ones). We conduct large-scale experiments under controlled evaluation conditions across diverse model families (e.g., Llama, Qwen, Gemma, Mistral, Phi, GPT, DeepSeek). Our findings reveal three key insights: (1) Better generators are better judges -- LLM evaluators' accuracy strongly correlates with their task performance, and much of the self-preference in capable models is legitimate. (2) Harmful self-preference persists, particularly when evaluator models perform poorly as generators on specific task instances. Stronger models exhibit more pronounced harmful bias when they err, though such incorrect generations are less frequent. (3) Inference-time scaling strategies, such as generating a long Chain-of-Thought before evaluation, effectively reduce the harmful self-preference. These results provide a more nuanced understanding of LLM-based evaluation and practical insights for improving its reliability.

[Arxiv](https://arxiv.org/abs/2504.03846)