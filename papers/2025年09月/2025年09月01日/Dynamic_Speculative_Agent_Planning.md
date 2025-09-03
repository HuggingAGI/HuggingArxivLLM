# 动态推测性智能体规划

发布时间：2025年09月01日

`Agent` `基础理论`

> Dynamic Speculative Agent Planning

# 摘要

> 尽管基于大型语言模型的智能体凭借在复杂任务中的出色表现推动了广泛应用，但高昂的延迟和推理成本使其在部署时仍面临严峻挑战。近期研究虽探索了多种推理加速方法，现有方案却存在明显局限：要么难以保持性能保真，要么需对路由模块进行大量离线训练，要么导致运营成本过高。更关键的是，在加速与其他性能指标的权衡上，用户几乎无法掌控。为此，我们提出动态推测规划（DSP）——一种异步在线强化学习框架，无需额外部署前准备，即可实现无损加速并显著降低成本。DSP通过优化端到端延迟与成本的联合目标，让从业者只需调整单个参数，就能将系统调至更快响应、更低成本，或这一连续区间内的任意状态。在两个标准智能体基准测试中，DSP的效率可与最快无损加速方法媲美，同时总成本降低30%，无效成本更是减少高达60%。相关代码与数据已开源，地址为https://github.com/guanyilin428/Dynamic-Speculative-Planning。

> Despite their remarkable success in complex tasks propelling widespread adoption, large language-model-based agents still face critical deployment challenges due to prohibitive latency and inference costs. While recent work has explored various methods to accelerate inference, existing approaches suffer from significant limitations: they either fail to preserve performance fidelity, require extensive offline training of router modules, or incur excessive operational costs. Moreover, they provide minimal user control over the tradeoff between acceleration and other performance metrics. To address these gaps, we introduce Dynamic Speculative Planning (DSP), an asynchronous online reinforcement learning framework that provides lossless acceleration with substantially reduced costs without requiring additional pre-deployment preparation. DSP explicitly optimizes a joint objective balancing end-to-end latency against dollar cost, allowing practitioners to adjust a single parameter that steers the system toward faster responses, cheaper operation, or any point along this continuum. Experiments on two standard agent benchmarks demonstrate that DSP achieves comparable efficiency to the fastest lossless acceleration method while reducing total cost by 30% and unnecessary cost up to 60%. Our code and data are available through https://github.com/guanyilin428/Dynamic-Speculative-Planning.

[Arxiv](https://arxiv.org/abs/2509.01920)