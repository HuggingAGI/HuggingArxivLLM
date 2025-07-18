# BootSeer：深入分析并缓解大规模LLM的训练过程中遇到的初始化瓶颈问题

发布时间：2025年07月16日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）训练过程中的启动开销问题，提出了一种优化框架Bootseer，以解决实际训练中的性能瓶颈。研究内容涉及LLM的实际应用优化，属于LLM应用分类。` `系统优化`

> BootSeer: Analyzing and Mitigating Initialization Bottlenecks in Large-Scale LLM Training

# 摘要

> 大型语言模型（LLMs）已成为现代AI的重要基石，不仅推动了自然语言处理的突破，还将应用扩展到涉及图像、音频和视频的多模态任务。与大多数计算软件一样，区分普通运行时性能和启动开销至关重要。此前研究主要关注运行时性能，即提升训练效率和稳定性。而本研究则聚焦于训练中日益关键的启动开销问题——训练任务开始执行前的延迟。启动开销在大型工业级LLMs中尤为重要，因为这类模型故障率更高，且多个团队在迭代更新-调试循环中运行。在我们的一个训练集群中，仅启动开销就浪费了超过3.5%的GPU时间。
    本研究基于真实生产数据，首次深入剖析了LLM训练启动开销。我们分析了启动成本的组成部分，量化了其直接影响，并研究了其如何随任务规模增长。这些洞察启发了Bootseer的设计——一个系统级优化框架，旨在解决三个主要启动瓶颈：容器镜像加载、运行时依赖安装和模型检查点恢复。为缓解这些瓶颈，Bootseer引入了三项技术：热块记录与预取、依赖快照和条纹HDFS-FUSE。Bootseer已在生产环境中部署，并在真实LLM训练负载上进行评估，实现了启动开销降低50%的显著效果。

> Large Language Models (LLMs) have become a cornerstone of modern AI, driving breakthroughs in natural language processing and expanding into multimodal jobs involving images, audio, and video. As with most computational software, it is important to distinguish between ordinary runtime performance and startup overhead. Prior research has focused on runtime performance: improving training efficiency and stability. This work focuses instead on the increasingly critical issue of startup overhead in training: the delay before training jobs begin execution. Startup overhead is particularly important in large, industrial-scale LLMs, where failures occur more frequently and multiple teams operate in iterative update-debug cycles. In one of our training clusters, more than 3.5% of GPU time is wasted due to startup overhead alone.
  In this work, we present the first in-depth characterization of LLM training startup overhead based on real production data. We analyze the components of startup cost, quantify its direct impact, and examine how it scales with job size. These insights motivate the design of Bootseer, a system-level optimization framework that addresses three primary startup bottlenecks: (a) container image loading, (b) runtime dependency installation, and (c) model checkpoint resumption. To mitigate these bottlenecks, Bootseer introduces three techniques: (a) hot block record-and-prefetch, (b) dependency snapshotting, and (c) striped HDFS-FUSE. Bootseer has been deployed in a production environment and evaluated on real LLM training workloads, demonstrating a 50% reduction in startup overhead.

[Arxiv](https://arxiv.org/abs/2507.12619)