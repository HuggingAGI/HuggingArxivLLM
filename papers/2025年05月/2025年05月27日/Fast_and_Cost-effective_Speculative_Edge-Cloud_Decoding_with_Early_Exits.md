# 快速且具成本效益的边缘-云协同解码，带提前退出机制

发布时间：2025年05月27日

`LLM应用

理由：这篇论文讨论了在边缘设备上部署大型语言模型的应用，特别是通过边缘-云端协作来优化模型的运行效率和性能，属于LLM的实际应用领域。` `边缘计算` `机器人`

> Fast and Cost-effective Speculative Edge-Cloud Decoding with Early Exits

# 摘要

> # 摘要
大型语言模型（LLMs）在智能手机、可穿戴设备和具身机器人等边缘设备上实现了多种应用。然而，其部署往往依赖于昂贵的基于云的API，导致高昂的运营成本，这限制了小型组织的使用，并引发了可持续性方面的担忧。某些LLMs可以部署在设备端，提供了一种成本较低的解决方案，同时降低了延迟并提高了隐私性。然而，受限的计算资源限制了可部署模型的规模和精度，因此需要在边缘和云端之间进行协作设计。

我们提出了一种快速且经济高效的推测式边缘-云端解码框架，服务器端运行大型目标模型，设备端运行小型草稿模型。通过在目标模型中引入提前退出机制，可以在验证过程中生成令牌，使客户端能够在最终验证前抢先生成后续令牌，从而利用空闲时间并增强边缘与云端之间的并行性。

使用NVIDIA Jetson Nano（客户端）和A100 GPU（服务器），配合Vicuna-68M（草稿）和Llama2-7B（目标）模型，我们的方法相较于基于云端的自回归解码，延迟降低了高达35%，并通过抢先生成草稿模型进一步提升了11%的性能。为了展示实际应用的可行性，我们将方法部署在Unitree Go2四足机器人上，采用基于视觉语言模型（VLM）的控制，相较于传统云端自回归解码，实现了21%的速度提升。这些结果证明了我们的框架在资源受限的边缘设备上实现实时LLM和VLM应用的潜力。


> Large Language Models (LLMs) enable various applications on edge devices such as smartphones, wearables, and embodied robots. However, their deployment often depends on expensive cloud-based APIs, creating high operational costs, which limit access for smaller organizations and raise sustainability concerns. Certain LLMs can be deployed on-device, offering a cost-effective solution with reduced latency and improved privacy. Yet, limited computing resources constrain the size and accuracy of models that can be deployed, necessitating a collaborative design between edge and cloud. We propose a fast and cost-effective speculative edge-cloud decoding framework with a large target model on the server and a small draft model on the device. By introducing early exits in the target model, tokens are generated mid-verification, allowing the client to preemptively draft subsequent tokens before final verification, thus utilizing idle time and enhancing parallelism between edge and cloud. Using an NVIDIA Jetson Nano (client) and an A100 GPU (server) with Vicuna-68M (draft) and Llama2-7B (target) models, our method achieves up to a 35% reduction in latency compared to cloud-based autoregressive decoding, with an additional 11% improvement from preemptive drafting. To demonstrate real-world applicability, we deploy our method on the Unitree Go2 quadruped robot using Vision-Language Model (VLM) based control, achieving a 21% speedup over traditional cloud-based autoregressive decoding. These results demonstrate the potential of our framework for real-time LLM and VLM applications on resource-constrained edge devices.

[Arxiv](https://arxiv.org/abs/2505.21594)