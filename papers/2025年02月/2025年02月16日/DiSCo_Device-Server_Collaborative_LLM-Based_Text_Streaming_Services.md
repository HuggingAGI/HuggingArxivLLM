# DiSCo：设备与服务器协同的文本流服务，基于大语言模型

发布时间：2025年02月16日

`LLM应用

摘要中的论文讨论了大型语言模型在实际应用中的部署和优化，特别是通过设备-服务器协作来提高用户体验和降低成本。这属于LLM的应用层面。` `互联网服务` `云计算`

> DiSCo: Device-Server Collaborative LLM-Based Text Streaming Services

# 摘要

> 大型语言模型（LLMs）在文本流服务中的崛起带来了成本和用户体验（QoE）的双重挑战，尤其是在满足实时交互中的首次生成响应时间（TTFT）和响应生成间隔时间（TBT）要求方面。实际测量显示，无论是基于服务器的部署还是设备端部署，都难以满足多样化的用户体验需求：服务器部署面临高昂成本和最后一跳问题（如互联网延迟和动态变化），而设备端LLM推理则受限于资源约束。

为应对这些挑战，我们提出了DiSCo——一种设备-服务器协作调度器。DiSCo通过自适应路由请求并在端点之间迁移响应生成，优化用户体验的同时保持成本约束。它采用成本感知调度，结合设备端LLM推理的可预测速度和服务器端推理的灵活容量，实时分配请求。此外，DiSCo引入了令牌级迁移机制，确保迁移过程中的令牌连续交付。在包括OpenAI GPT、DeepSeek等商业服务以及LLaMA3等开源部署的实际工作负载评估中，DiSCo显著提升了用户体验，将尾部TTFT降低了11-52%，平均TTFT降低了6-78%，同时通过其迁移机制将服务成本降低了高达84%，同时保持了可比的用户体验水平。

> The rapid rise of large language models (LLMs) in text streaming services has introduced significant cost and Quality of Experience (QoE) challenges in serving millions of daily requests, especially in meeting Time-To-First-Token (TTFT) and Time-Between-Token (TBT) requirements for real-time interactions. Our real-world measurements show that both server-based and on-device deployments struggle to meet diverse QoE demands: server deployments face high costs and last-hop issues (e.g., Internet latency and dynamics), while on-device LLM inference is constrained by resources.
  We introduce DiSCo, a device-server cooperative scheduler designed to optimize users' QoE by adaptively routing requests and migrating response generation between endpoints while maintaining cost constraints. DiSCo employs cost-aware scheduling, leveraging the predictable speed of on-device LLM inference with the flexible capacity of server-based inference to dispatch requests on the fly, while introducing a token-level migration mechanism to ensure consistent token delivery during migration. Evaluations on real-world workloads -- including commercial services like OpenAI GPT and DeepSeek, and open-source deployments such as LLaMA3 -- show that DiSCo can improve users' QoE by reducing tail TTFT (11-52\%) and mean TTFT (6-78\%) across different model-device configurations, while dramatically reducing serving costs by up to 84\% through its migration mechanism while maintaining comparable QoE levels.

[Arxiv](https://arxiv.org/abs/2502.11417)