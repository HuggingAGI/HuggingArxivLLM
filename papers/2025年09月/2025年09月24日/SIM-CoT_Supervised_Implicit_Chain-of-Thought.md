# SIM-CoT: 监督隐式思维链

发布时间：2025年09月24日

`LLM应用` `基础理论`

> SIM-CoT: Supervised Implicit Chain-of-Thought

# 摘要

> 隐式思维链（CoT）方法为大型语言模型（LLMs）的显式CoT推理提供了一种极具潜力且token高效的替代方案，然而持续存在的性能差距却限制了其实际应用。我们通过增加隐式CoT方法的计算资源，发现了一个核心的潜在不稳定性问题：为提升性能而增加隐式推理token数量时，训练过程常会陷入不稳定甚至崩溃。分析显示，这种不稳定性源于潜在表示趋同且丧失语义多样性，而这一问题的根源在于现有隐式CoT方法缺乏足够的步骤级监督。为解决此问题，我们提出SIM-CoT——一种即插即用的训练模块，它通过引入步骤级监督来稳定并丰富潜在推理空间。具体来说，SIM-CoT在训练时采用辅助解码器，将每个隐式token与对应的显式推理步骤对齐，确保潜在状态能捕捉到独特且有意义的信息。该辅助解码器在推理阶段被移除，因此在不增加任何额外开销的情况下，仍能保持隐式CoT方法的计算效率。此外，辅助解码器还能将每个潜在token投射到显式推理词汇表中，从而赋予隐式推理可解释性，支持对每一步语义角色的可视化与诊断。SIM-CoT显著提升了多种隐式CoT方法的域内准确率和域外稳定性：在GPT-2上，Coconut等基线模型性能提升8.2%；在LLaMA-3.1 8B上，CODI模型提升3.0%。SIM-CoT还展现出优异的可扩展性，在GPT-2上以2.3倍的token效率超越显式CoT基线2.1%，同时在LLaMA-3.1 8B等更大模型上大幅缩小了性能差距。

> Implicit Chain-of-Thought (CoT) methods present a promising, token-efficient alternative to explicit CoT reasoning in Large Language Models (LLMs), but a persistent performance gap has limited the application of implicit CoT. We identify a core latent instability issue by scaling the computational budget of implicit CoT approaches: as we increase the number of implicit reasoning tokens to enhance performance, the training process often becomes unstable and collapses. Our analysis reveals that this instability arises from the latent representations becoming homogeneous and losing their semantic diversity, a failure caused by insufficient step-level supervision in existing implicit CoT approaches. To address this issue, we propose SIM-CoT, a plug-and-play training module that introduces step-level supervision to stabilize and enrich the latent reasoning space. Specifically, SIM-CoT employs an auxiliary decoder during training to align each implicit token with its corresponding explicit reasoning step, ensuring that latent states capture distinct and meaningful information. The proposed auxiliary decoder is removed during inference, preserving the computational efficiency of implicit CoT methods with no added overhead. In addition, the auxiliary decoder affords interpretability of implicit reasoning by projecting each latent token onto an explicit reasoning vocabulary, enabling per-step visualization of semantic roles and diagnosis. SIM-CoT significantly enhances both the in-domain accuracy and out-of-domain stability of various implicit CoT methods, boosting baselines like Coconut by +8.2% on GPT-2 and CODI by +3.0% on LLaMA-3.1 8B. Demonstrating strong scalability, SIM-CoT also surpasses the explicit CoT baseline on GPT-2 by 2.1% with 2.3\times greater token efficiency, while substantially closing the performance gap on larger models like LLaMA-3.1 8B.

[Arxiv](https://arxiv.org/abs/2509.20317)