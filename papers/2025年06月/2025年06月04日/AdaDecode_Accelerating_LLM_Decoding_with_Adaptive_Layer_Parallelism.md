# # AdaDecode：利用自适应层并行加速LLM解码过程

发布时间：2025年06月04日

`LLM应用` `计算机体系结构`

> AdaDecode: Accelerating LLM Decoding with Adaptive Layer Parallelism

# 摘要

> 大型语言模型（LLMs）在长内容生成（如长链式推理）中的应用日益广泛，但解码效率成为了关键瓶颈。自回归解码的生成过程是串行的，这导致了其固有的局限性：每个token必须生成后，下一个才能开始处理。这种串行依赖关系限制了现代硬件并行处理能力的充分发挥。现有的加速方法如推测式解码和层跳过虽有一定潜力，但存在明显缺陷：推测式解码依赖辅助模型，获取困难且增加内存开销；层跳过则可能因缺少跳过层的键值缓存导致输出不一致。本研究提出了一种名为AdaDecode的方法，无需辅助模型或修改原模型参数，即可实现加速，同时保证输出一致性。AdaDecode基于以下观察：许多token可以在中间层准确生成，因为一旦模型达到一定置信度，后续层通常不会显著改变预测结果。通过在高置信度时自适应地在中间层生成token，AdaDecode可立即开始计算下一个token。对于早期预测的token，剩余的层计算会被延迟，并在需要时与后续token的计算并行执行，从而最大化硬件利用率并减少解码延迟。最后的验证步骤确保早期预测与标准自回归解码结果一致，保持输出一致性。实验结果表明，AdaDecode在多种生成任务中均实现了高达1.73倍的加速，同时保证了与标准自回归解码一致的输出质量，展现了其优越的解码吞吐量。


> Large language models (LLMs) are increasingly used for long-content generation (e.g., long Chain-of-Thought reasoning) where decoding efficiency becomes a critical bottleneck: Autoregressive decoding is inherently limited by its sequential token generation process, where each token must be generated before the next can be processed. This sequential dependency restricts the ability to fully leverage modern hardware's parallel processing capabilities. Existing methods like speculative decoding and layer skipping offer potential speedups but have notable drawbacks: speculative decoding relies on an auxiliary "drafter" model, which can be challenging to acquire and increases memory overhead, while layer skipping may introduce discrepancies in the outputs due to the missing key-value cache at skipped layers. In this work, we propose AdaDecode, which accelerates LLM decoding without requiring auxiliary models or changes to the original model parameters, while ensuring output consistency. AdaDecode leverages the insight that many tokens can accurately be generated at intermediate layers, as further layers often do not significantly alter predictions once the model reaches a certain confidence. By adaptively generating tokens at intermediate layers when confidence is high, AdaDecode enables the next token's computation to begin immediately. The remaining layer computations for early-predicted tokens are deferred and executed in parallel with subsequent tokens when needed, maximizing hardware utilization and reducing decoding latency. A final verification step ensures that early predictions match the results of standard autoregressive decoding, preserving output parity. Experiments across diverse generation tasks shows that AdaDecode consistently achieves superior decoding throughput with up to 1.73x speedup, while guaranteeing output parity with standard autoregressive decoding.

[Arxiv](https://arxiv.org/abs/2506.03700)