# 借助基于梯度的自我反思抑制多模态幻觉

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Mitigating Multimodal Hallucinations via Gradient-based Self-Reflection

# 摘要

> 多模态大型语言模型的幻觉由文本-视觉偏差和共现偏差导致：前者体现为决策时过度依赖文本信息，后者则源于训练数据中抽象出的统计对象配对模式。现有缓解方法多以启发式策略处理这些偏差，却忽略了实例间偏差水平的波动。为此，我们首先提出基于梯度的自反思方法，用于估计各类标记（视觉、提示及先前输出）的影响程度。基于这一估计结果，我们可进一步识别与对象相关的视觉标记，并将其整合到感知影响的对比解码框架中，从而同时缓解两种偏差。该方法无需额外资源支持（如昂贵的微调、额外模型或数据统计），大量实验证实其能有效减少幻觉，在LLaVA-QA90数据集上准确率提升高达92%。

> Hallucinations in multimodal large language model are caused by the text-visual bias and the co-occurrence bias. The former reflects an over-reliance on text information in the decision-making process, while the latter arises from the statistical object-pairing patterns abstracted from the training data. Existing mitigation methods heuristically address these biases without understanding the fluctuating bias level across the instances. We first propose estimating the influence of respective token types (visual, prompt, and previous outputs) using a gradient-based self-reflection method. The estimated token influence further enables the detection of object-related visual tokens and their integration into an influence-aware contrastive decoding framework to mitigate both types of biases simultaneously. Our method operates without the need for additional resources, such as costly fine-tuning, extra models, or data statistics. Extensive experiments show it effectively reduces hallucinations, achieving up to a 92% accuracy increase on LLaVA-QA90.

[Arxiv](https://arxiv.org/abs/2509.03113)