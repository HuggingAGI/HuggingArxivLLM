# 通过感知-生成解耦与异步流水线执行增强具身AI智能体

发布时间：2025年09月11日

`Agent` `基础理论`

> Boosting Embodied AI Agents through Perception-Generation Disaggregation and Asynchronous Pipeline Execution

# 摘要

> 具身AI系统在动态环境中运行，需无缝整合感知与生成模块，以应对高频的输入输出需求。传统顺序计算模式虽能保证准确性，但在满足现实应用所需的"思考"频率上存在显著局限。为此，我们提出Auras——一个算法与系统协同设计的推理框架，旨在提升具身AI智能体的推理频率。Auras通过解耦感知与生成模块，并为二者提供可控的流水线并行，实现了高稳定吞吐量。针对并行度提升时出现的数据陈旧问题，Auras构建了感知与生成模块共享的公共上下文，确保了具身智能体的准确性。实验结果显示，Auras平均提升吞吐量2.54倍，同时准确率达到原始水平的102.7%，有效突破了顺序计算的限制，实现了高吞吐量。

> Embodied AI systems operate in dynamic environments, requiring seamless integration of perception and generation modules to process high-frequency input and output demands. Traditional sequential computation patterns, while effective in ensuring accuracy, face significant limitations in achieving the necessary "thinking" frequency for real-world applications. In this work, we present Auras, an algorithm-system co-designed inference framework to optimize the inference frequency of embodied AI agents. Auras disaggregates the perception and generation and provides controlled pipeline parallelism for them to achieve high and stable throughput. Faced with the data staleness problem that appears when the parallelism is increased, Auras establishes a public context for perception and generation to share, thereby promising the accuracy of embodied agents. Experimental results show that Auras improves throughput by 2.54x on average while achieving 102.7% of the original accuracy, demonstrating its efficacy in overcoming the constraints of sequential computation and providing high throughput.

[Arxiv](https://arxiv.org/abs/2509.09560)