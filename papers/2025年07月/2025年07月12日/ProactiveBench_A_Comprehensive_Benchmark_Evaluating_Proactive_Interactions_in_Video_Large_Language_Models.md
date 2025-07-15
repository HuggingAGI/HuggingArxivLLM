# ProactiveBench：全面评估视频大语言模型主动交互能力的基准测试

发布时间：2025年07月12日

`LLM应用

理由：这篇论文探讨了多模态对话系统的主动交互能力，特别是多轮对话的响应时机。它引入了ProactiveBench作为评估基准，并提出了PAUC指标，考虑了模型响应时间的动态变化。这些内容主要集中在多模态对话系统的应用和评估上，属于LLM的应用层面。` `人工智能` `对话系统`

> ProactiveBench: A Comprehensive Benchmark Evaluating Proactive Interactions in Video Large Language Models

# 摘要

> 多模态对话系统研究的热度不断攀升，主动交互能力逐渐崭露头角。作为传统轮次对话的替代方案，用户如今更期待多模态系统能够主动作为，比如在视频播放时实时自主决定多轮对话的响应时机。为了推动这一新兴领域的进步，我们推出了ProactiveBench，这是首个全面评估系统主动交互能力的基准。鉴于模型响应生成的时间戳存在差异，我们进一步提出了PAUC，这是首个考虑模型响应时间动态的指标。这一创新使主动交互场景下的系统评估更加精准。通过对ProactiveBench上各种基线系统的全面测试以及对用户偏好的研究，我们发现PAUC与人类偏好高度契合，而传统评估指标通常仅关注响应的文本内容。这些研究表明，PAUC为用户在主动交互场景下的体验提供了更真实的评估。项目主页：https://github.com/yellow-binary-tree/ProactiveBench

> With the growing research focus on multimodal dialogue systems, the capability for proactive interaction is gradually gaining recognition. As an alternative to conventional turn-by-turn dialogue, users increasingly expect multimodal systems to be more initiative, for example, by autonomously determining the timing of multi-turn responses in real time during video playback. To facilitate progress in this emerging area, we introduce ProactiveBench, the first comprehensive benchmark to evaluate a system's ability to engage in proactive interaction. Since model responses are generated at varying timestamps, we further propose PAUC, the first metric that accounts for the temporal dynamics of model responses. This enables a more accurate evaluation of systems operating in proactive settings. Through extensive benchmarking of various baseline systems on ProactiveBench and a user study of human preferences, we show that PAUC is in better agreement with human preferences than traditional evaluation metrics, which typically only consider the textual content of responses. These findings demonstrate that PAUC provides a more faithful assessment of user experience in proactive interaction scenarios. Project homepage: https://github.com/yellow-binary-tree/ProactiveBench

[Arxiv](https://arxiv.org/abs/2507.09313)