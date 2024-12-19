# 螃蟹：在黑箱环境下通过自动生成方式消耗资源来实施 LLM-DoS 攻击

发布时间：2024年12月18日

`LLM应用` `网络安全` `语言模型`

> Crabs: Consuming Resrouce via Auto-generation for LLM-DoS Attack under Black-box Settings

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了非凡的性能。然而，LLMs 仍易遭受外部威胁，尤其是拒绝服务（DoS）攻击。具体而言，LLM-DoS 攻击意在耗尽计算资源并阻断服务。但此前的工作多聚焦于开展白盒攻击，忽视了黑盒情形。在此项工作中，我们提出了一种专为黑盒 LLMs 设计的自动化算法，名为 LLM-DoS 攻击自动生成（AutoDoS）。AutoDoS 引入了 DoS 攻击树，并优化了提示节点的覆盖范围，以增强黑盒环境下的有效性。我们的方法能够凭借提示节点的语义改进，以更强的隐蔽性绕过现有的防御。另外，我们发现，在基本 DoS 提示中植入长度木马有助于达成更高的攻击效能。实验结果显示，AutoDoS 使服务响应延迟增大超过 250 倍，致使 GPU 利用率和内存使用出现严重的资源消耗。我们的代码可在 url{https://github.com/shuita2333/AutoDoS}获取。

> Large Language Models (LLMs) have demonstrated remarkable performance across diverse tasks. LLMs continue to be vulnerable to external threats, particularly Denial-of-Service (DoS) attacks. Specifically, LLM-DoS attacks aim to exhaust computational resources and block services. However, prior works tend to focus on performing white-box attacks, overlooking black-box settings. In this work, we propose an automated algorithm designed for black-box LLMs, called Auto-Generation for LLM-DoS Attack (AutoDoS). AutoDoS introduces DoS Attack Tree and optimizes the prompt node coverage to enhance effectiveness under black-box conditions. Our method can bypass existing defense with enhanced stealthiness via semantic improvement of prompt nodes. Furthermore, we reveal that implanting Length Trojan in Basic DoS Prompt aids in achieving higher attack efficacy. Experimental results show that AutoDoS amplifies service response latency by over 250 $\times \uparrow$, leading to severe resource consumption in terms of GPU utilization and memory usage. Our code is available at \url{https://github.com/shuita2333/AutoDoS}.

[Arxiv](https://arxiv.org/abs/2412.13879)