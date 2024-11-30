# 通过结合 LLM 技术与崩溃重用策略，我们致力于对 BusyBox 进行高效模糊测试，以揭示隐藏的嵌入式软件漏洞。

发布时间：2024年03月06日

`LLM应用`

> Fuzzing BusyBox: Leveraging LLM and Crash Reuse for Embedded Bug Unearthing

# 摘要

> BusyBox这款开源软件将三百多个核心Linux命令打包进单个可执行程序，在各类Linux嵌入式设备中无所不在。然而，一旦BusyBox出现漏洞，将可能引发连锁反应，波及众多设备。鉴于其广泛应用，本研究聚焦于深入分析BusyBox。研究发现，许多实际嵌入式产品仍在使用老旧版本的BusyBox，故我们决定对其进行模糊测试。作为关键的软件测试手段，模糊测试旨在通过引发程序崩溃并细致排查来找出潜在的安全漏洞。在这项研究中，我们创新性地引入两种强化软件测试的方法。首先，我们利用大型语言模型（LLM）智能生成针对特定目标的初始测试样本，大幅提升了模糊测试触发崩溃的概率，充分展示了LLM在解决这一原本劳动强度极高的初始样本生成问题上的高效能力。其次，我们在对新目标进行模糊测试前，巧妙地循环利用从相似测试目标积累的崩溃数据，从而大大加速了繁琐的模糊测试进程。实验结果显示，即使未采用传统的模糊测试方法，我们也成功在最新版BusyBox中发现了崩溃点，有力证明了LLM与崩溃数据复用技术在提升软件测试效能和改善嵌入式系统漏洞检测方面的显著效果。同时，为了深入理解最新BusyBox中的崩溃特性，我们还进行了人工分类分析。

> BusyBox, an open-source software bundling over 300 essential Linux commands into a single executable, is ubiquitous in Linux-based embedded devices. Vulnerabilities in BusyBox can have far-reaching consequences, affecting a wide array of devices. This research, driven by the extensive use of BusyBox, delved into its analysis. The study revealed the prevalence of older BusyBox versions in real-world embedded products, prompting us to conduct fuzz testing on BusyBox. Fuzzing, a pivotal software testing method, aims to induce crashes that are subsequently scrutinized to uncover vulnerabilities. Within this study, we introduce two techniques to fortify software testing. The first technique enhances fuzzing by leveraging Large Language Models (LLM) to generate target-specific initial seeds. Our study showed a substantial increase in crashes when using LLM-generated initial seeds, highlighting the potential of LLM to efficiently tackle the typically labor-intensive task of generating target-specific initial seeds. The second technique involves repurposing previously acquired crash data from similar fuzzed targets before initiating fuzzing on a new target. This approach streamlines the time-consuming fuzz testing process by providing crash data directly to the new target before commencing fuzzing. We successfully identified crashes in the latest BusyBox target without conducting traditional fuzzing, emphasizing the effectiveness of LLM and crash reuse techniques in enhancing software testing and improving vulnerability detection in embedded systems. Additionally, manual triaging was performed to identify the nature of crashes in the latest BusyBox.

[Arxiv](https://arxiv.org/abs/2403.03897)