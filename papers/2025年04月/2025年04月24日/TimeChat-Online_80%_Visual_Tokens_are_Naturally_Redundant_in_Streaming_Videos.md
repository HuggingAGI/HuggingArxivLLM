# TimeChat-Online：流媒体视频中80%的视觉标记天然冗余

发布时间：2025年04月24日

`LLM应用` `视频处理` `流媒体`

> TimeChat-Online: 80% Visual Tokens are Naturally Redundant in Streaming Videos

# 摘要

> 在线视频平台的蓬勃发展，尤其是直播服务的崛起，催生了对实时视频理解系统的迫切需求。这些系统需要处理连续的视频流并即时响应用户查询，这对现有的视频大语言模型（VideoLLMs）提出了独特挑战。虽然现有的VideoLLMs在处理完整视频方面表现出色，但它们在流媒体场景中表现欠佳，主要因为它们难以高效处理密集冗余的帧。我们推出了TimeChat-Online，一款开创性的在线视频大语言模型，重新定义了实时视频交互体验。其核心是我们创新的差异令牌丢弃（DTD）模块，该模块巧妙地解决了流媒体视频中视觉冗余的根本问题。受人类视觉感知中的“变化盲视”现象启发，DTD在过滤掉帧间静态冗余内容的同时，完整保留了有意义的时间变化。实验结果令人惊艳：DTD在保持98%的StreamingBench性能水平的同时，将视频令牌减少了82.8%，揭示了流媒体视频中超过80%的视觉内容天然冗余，无需额外语言指导即可实现。为实现无缝实时交互，我们推出了TimeChat-Online-139K，这是一个全面的流媒体视频数据集，涵盖了多样化的交互模式，包括回溯追踪、当前感知和未来响应等场景。TimeChat-Online独特的主动响应能力，通过DTD持续监控视频场景过渡而自然实现，使其在传统方法中独树一帜。我们的评估结果表明，TimeChat-Online在流媒体基准测试（StreamingBench和OvOBench）中表现卓越，并在长视频任务（如Video-MME和MLVU）中保持了极具竞争力的水准。

> The rapid growth of online video platforms, particularly live streaming services, has created an urgent need for real-time video understanding systems. These systems must process continuous video streams and respond to user queries instantaneously, presenting unique challenges for current Video Large Language Models (VideoLLMs). While existing VideoLLMs excel at processing complete videos, they face significant limitations in streaming scenarios due to their inability to handle dense, redundant frames efficiently. We introduce TimeChat-Online, a novel online VideoLLM that revolutionizes real-time video interaction. At its core lies our innovative Differential Token Drop (DTD) module, which addresses the fundamental challenge of visual redundancy in streaming videos. Drawing inspiration from human visual perception's Change Blindness phenomenon, DTD preserves meaningful temporal changes while filtering out static, redundant content between frames. Remarkably, our experiments demonstrate that DTD achieves an 82.8% reduction in video tokens while maintaining 98% performance on StreamingBench, revealing that over 80% of visual content in streaming videos is naturally redundant without requiring language guidance. To enable seamless real-time interaction, we present TimeChat-Online-139K, a comprehensive streaming video dataset featuring diverse interaction patterns including backward-tracing, current-perception, and future-responding scenarios. TimeChat-Online's unique Proactive Response capability, naturally achieved through continuous monitoring of video scene transitions via DTD, sets it apart from conventional approaches. Our extensive evaluation demonstrates TimeChat-Online's superior performance on streaming benchmarks (StreamingBench and OvOBench) and maintaining competitive results on long-form video tasks such as Video-MME and MLVU.

[Arxiv](https://arxiv.org/abs/2504.17343)