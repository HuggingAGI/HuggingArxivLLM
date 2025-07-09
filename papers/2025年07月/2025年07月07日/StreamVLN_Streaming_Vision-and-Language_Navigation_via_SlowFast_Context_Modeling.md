# StreamVLN：基于慢快上下文建模的流式视觉语言导航系统

发布时间：2025年07月07日

`Agent` `人工智能` `机器人导航`

> StreamVLN: Streaming Vision-and-Language Navigation via SlowFast Context Modeling

# 摘要

> # 摘要
在真实环境中，视觉语言导航（VLN）要求智能体实时处理连续视觉流，并根据语言指令快速生成动作。尽管基于视频的大语言模型（Video-LLMs）推动了VLN领域的进展，但现有方法在精细视觉理解、长期上下文建模和计算效率之间往往难以兼顾。为此，我们提出了StreamVLN——一个采用混合慢快上下文建模策略的流式VLN框架。该框架通过交错处理视觉、语言和动作输入，支持高效的多模态推理。具体来说，快速流对话上下文利用活动对话的滑动窗口，实现快速响应式动作生成；而慢更新的记忆上下文则采用3D感知的令牌剪枝策略，有效压缩历史视觉状态。凭借这一创新设计，StreamVLN实现了高效的KV缓存复用，支持长视频流处理，同时保持固定上下文大小和推理成本。在VLN-CE基准测试中，StreamVLN不仅达到了最先进性能，还实现了稳定低延迟，确保了在真实环境中的鲁棒性和高效性。项目页面：\href{https://streamvln.github.io/}{https://streamvln.github.io/}。

> Vision-and-Language Navigation (VLN) in real-world settings requires agents to process continuous visual streams and generate actions with low latency grounded in language instructions. While Video-based Large Language Models (Video-LLMs) have driven recent progress, current VLN methods based on Video-LLM often face trade-offs among fine-grained visual understanding, long-term context modeling and computational efficiency. We introduce StreamVLN, a streaming VLN framework that employs a hybrid slow-fast context modeling strategy to support multi-modal reasoning over interleaved vision, language and action inputs. The fast-streaming dialogue context facilitates responsive action generation through a sliding-window of active dialogues, while the slow-updating memory context compresses historical visual states using a 3D-aware token pruning strategy. With this slow-fast design, StreamVLN achieves coherent multi-turn dialogue through efficient KV cache reuse, supporting long video streams with bounded context size and inference cost. Experiments on VLN-CE benchmarks demonstrate state-of-the-art performance with stable low latency, ensuring robustness and efficiency in real-world deployment. The project page is: \href{https://streamvln.github.io/}{https://streamvln.github.io/}.

[Arxiv](https://arxiv.org/abs/2507.05240)