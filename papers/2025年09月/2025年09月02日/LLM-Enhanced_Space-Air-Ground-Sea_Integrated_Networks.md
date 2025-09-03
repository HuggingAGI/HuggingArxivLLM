# LLM赋能的空天地海一体化网络

发布时间：2025年09月02日

`LLM应用` `交通运输`

> LLM-Enhanced Space-Air-Ground-Sea Integrated Networks

# 摘要

> 空天地海一体化网络（SAGSIN）概念虽有望实现全球无缝多媒体连接，但实际部署仍面临两大障碍。其一，高速卫星、空中中继及海面平台受信道状态信息（CSI）过时困扰，导致基于反馈的适配效果大打折扣；其二，协议栈内数据速率差异悬殊：太比特级空间光链路与千比特级水下声链路共存。本文提出，通过在无线电、光学和声学轨迹上联合训练单一大型语言模型（LLM）骨干网络，可构建统一的数据驱动适配层，同时解决SAGSIN协议栈中CSI快速老化与带宽差异悬殊的问题。具体来看，基于LLM的远程信道预测器可提前多个相干间隔预测最强时延-多普勒分量，即便信道剧烈波动也能实现近容量接收。此外，我们的LLM语义编码器能将原始传感器数据载荷转化为面向任务的令牌，大幅降低沿海水下链路高保真图像传输的信噪比（SNR）需求，并借助语义通信突破数据速率限制。整合上述工具后，便能形成跨无线电、光学与声学信道的介质无关适配层。最后，我们展望了端侧模型压缩、多模态保真度控制、跨层资源编排及可信运行等极具潜力的开放研究方向，为从实验室原型走向实地部署指明了路径。

> The space-air-ground-sea integrated networking (SAGSIN) concept promises seamless global multimedia connectivity, yet two obstacles still limit its practical deployment. Firstly, high-velocity satellites, aerial relays and sea-surface platforms suffer from obsolete channel state information (CSI), undermining feedback-based adaptation. Secondly, data-rate disparity across the protocol stack is extreme: terabit optical links in space coexist with kilobit acoustic under-water links. This article shows that a single large language model (LLM) backbone, trained jointly on radio, optical and acoustic traces, can provide a unified, data-driven adaptation layer that addresses both rapid CSI ageing and severe bandwidth disparity across the SAGSIN protocol stack. Explicitly, an LLM-based long-range channel predictor forecasts the strongest delay-Doppler components several coherence intervals ahead, facilitating near-capacity reception despite violent channel fluctuations. Furthermore, our LLM-based semantic encoder turns raw sensor payloads into task-oriented tokens. This substantially reduces the SNR required for high-fidelity image delivery in a coastal underwater link, circumventing the data rate limitation by semantic communications. Inclusion of these tools creates a medium-agnostic adaptation layer that spans radio, optical and acoustic channels. We conclude with promising open research directions in on-device model compression, multimodal fidelity control, cross-layer resource orchestration and trustworthy operation, charting a path from laboratory prototypes to field deployment.

[Arxiv](https://arxiv.org/abs/2509.02540)