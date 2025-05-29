# <翻译失败>

发布时间：2025年05月22日

`LLM应用` `计算机网络`

> Resilient LLM-Empowered Semantic MAC Protocols via Zero-Shot Adaptation and Knowledge Distillation

# 摘要

> 基于神经网络的介质访问控制 (MAC) 协议模型 (NPMs) 能够通过特定站点操作有效提升网络吞吐量，但其在脱离训练环境后表现脆弱，例如用户设备 (UE) 数量的变化会严重影响吞吐量。为增强这些模型对环境变化的鲁棒性，我们提出了三种全新的语义 MAC 协议框架，这些框架由大型语言模型 (LLMs) 提供支持。

首先，我们引入了一种基于令牌的协议模型 (TPM)，其中 LLM 生成 MAC 信号消息。通过编辑 LLM 的指令提示，TPM 可以实现快速适应，这种适应能力还可以通过基于 LLM 的自动化提示优化器 TextGrad 进一步增强。然而，TPM 的推理速度虽快，但由于缺乏与变化环境的实际交互，结果较为粗略，且由于 LLM 的规模庞大，计算开销也较大。

为了提高吞吐量和计算效率，我们开发了 T2NPM，通过知识蒸馏 (KD) 将 TPM 的知识迁移并增强到 NPM 中。结合 TPM 和 T2NPM，我们提出了 T3NPM，该模型在早期阶段使用 TPM，随后切换到 T2NPM。为了优化这一阶段切换，我们设计了一个新的元韧性指标，该指标量化了环境变化后对未知目标吞吐量的韧性。

仿真结果表明，与传统 NPM 相比，T3NPM 的元韧性提升了 20.56%，同时计算成本降低了 19.8 倍（以 FLOPS 为单位）。

> Neural network-based medium access control (MAC) protocol models (NPMs) improve goodput through site-specific operations but are vulnerable to shifts from their training network environments, such as changes in the number of user equipments (UEs) severely degrade goodput. To enhance resilience against such environmental shifts, we propose three novel semantic MAC protocol frameworks empowered by large language models (LLMs). First, we introduce a token-based protocol model (TPM), where an LLM generates MAC signaling messages. By editing LLM instruction prompts, TPM enables instant adaptation, which can be further enhanced by TextGrad, an LLM-based automated prompt optimizer. TPM inference is fast but coarse due to the lack of real interactions with the changed environment, and computationally intensive due to the large size of the LLM. To improve goodput and computation efficiency, we develop T2NPM, which transfers and augments TPM knowledge into an NPM via knowledge distillation (KD). Integrating TPM and T2NPM, we propose T3NPM, which employs TPM in the early phase and switches to T2NPM later. To optimize this phase switching, we design a novel metric of meta-resilience, which quantifies resilience to unknown target goodput after environmental shifts. Simulations corroborate that T3NPM achieves 20.56% higher meta-resilience than NPM with 19.8x lower computation cost than TPM in FLOPS.

[Arxiv](https://arxiv.org/abs/2505.21518)