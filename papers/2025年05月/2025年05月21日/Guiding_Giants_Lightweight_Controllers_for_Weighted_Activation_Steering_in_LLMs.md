# 指引巨轮：LLMs的轻量级加权激活引导控制器

发布时间：2025年05月21日

`LLM理论` `人工智能` `机器学习`

> Guiding Giants: Lightweight Controllers for Weighted Activation Steering in LLMs

# 摘要

> 控制大型语言模型（LLM）的不良行为（如生成不安全内容或未能遵守安全指南）通常依赖于成本高昂的微调。现有激活引导方法虽然提供了推理时的控制选项，但普遍缺乏精细且自适应的机制。我们提出了一种创新方法，通过在推理过程中集成轻量级、可训练的控制器网络实现更智能的控制。该控制器网络能够观察特定的中间LLM激活状态，并预测全局缩放因子和层特定权重。这些预测结果会动态调节一个引导补丁的强度，该补丁源自预计算的“拒绝方向”向量，在生成过程中跨LLM各层应用。我们的控制器通过分析有害和良性提示的激活数据进行训练，能够有区别地应用细腻且层感知的干预，主要针对有害输入激活引导。实验结果表明，与基线LLM相比，我们的加权引导控制器显著提高了拒绝率，实现了有针对性的行为修改，而无需更改原始模型参数。在Llama-3.1-8B、Llama-3.2-1B和Mistral-7B上的实验验证了我们的方法优于现有方法，提供了一种在推理时对LLM行为进行精细控制的有效且自适应的解决方案。


> Controlling undesirable Large Language Model (LLM) behaviors, such as the generation of unsafe content or failing to adhere to safety guidelines, often relies on costly fine-tuning. Activation steering provides an alternative for inference-time control, but existing methods typically lack fine-grained, adaptive mechanisms. We introduce a novel approach using a lightweight, trainable controller network integrated during inference. This controller network observes specific intermediate LLM activations and predicts both a global scaling factor and layer-specific weights. The predicted global scaling factor and layer-specific weights then dynamically modulate the intensity of a steering patch, derived from a pre-computed "refusal direction" vector, applied across the LLM's layers during generation. Trained on activations from both harmful and benign prompts, our controller learns to discriminatively apply nuanced, layer-aware interventions, activating steering primarily for harmful inputs. Experiments using safety benchmarks like ToxicChat & In-The-Wild Jailbreak Prompts demonstrate that our weighted steering controller significantly increases refusal rates compared to the base LLM, achieving targeted behavioral modification without altering the original model parameters. Our experiments with Llama-3.1-8B, Llama-3.2-1B & Mistral-7B show our approach outperforms existing methods, presenting an efficient and adaptive method for fine-grained control over LLM behavior at inference time.

[Arxiv](https://arxiv.org/abs/2505.20309)