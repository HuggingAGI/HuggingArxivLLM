# Explorer：探索驱动的网络轨迹合成技术扩展，应用于多模态网络智能体

发布时间：2025年02月18日

`Agent` `智能体` `数据科学`

> Explorer: Scaling Exploration-driven Web Trajectory Synthesis for Multimodal Web Agents

# 摘要

> 大型多模态模型（LMMs）的成功应用为自主完成复杂网络任务的智能体开辟了广阔的前景。尽管开源的LMM代理在离线评估基准上取得了显著进展，但在更贴近现实的在线环境中，它们的表现仍与人类水平相去甚远。一个关键挑战在于缺乏跨领域多样且大规模的轨迹级数据集，而这些数据集的获取成本高昂。本文提出了一种创新的合成方法，成功构建了迄今为止规模最大、最多样化的轨迹级数据集，包含超过94,000个成功的多模态网络轨迹，覆盖49,000个独特的URL、720,000张截图和3300万个网络元素。通过广泛的网络探索和优化，我们有效获取了多样化的任务意图。每个成功轨迹的平均成本仅为28美分，使其对社区中的广大研究者和开发者都极具吸引力。基于这一数据集，我们开发了多模态网络代理Explorer，并在包括Mind2Web-Live、Multimodal-Mind2Web和MiniWob++在内的多个离线及在线基准测试中展现了卓越性能。我们的研究还揭示，数据规模是提升网络代理能力的关键因素。我们希望通过这项研究，推动基于LMM的智能体研究迈向更大规模和更广泛应用。

> Recent success in large multimodal models (LMMs) has sparked promising applications of agents capable of autonomously completing complex web tasks. While open-source LMM agents have made significant advances in offline evaluation benchmarks, their performance still falls substantially short of human-level capabilities in more realistic online settings. A key bottleneck is the lack of diverse and large-scale trajectory-level datasets across various domains, which are expensive to collect. In this paper, we address this challenge by developing a scalable recipe to synthesize the largest and most diverse trajectory-level dataset to date, containing over 94K successful multimodal web trajectories, spanning 49K unique URLs, 720K screenshots, and 33M web elements. In particular, we leverage extensive web exploration and refinement to obtain diverse task intents. The average cost is 28 cents per successful trajectory, making it affordable to a wide range of users in the community. Leveraging this dataset, we train Explorer, a multimodal web agent, and demonstrate strong performance on both offline and online web agent benchmarks such as Mind2Web-Live, Multimodal-Mind2Web, and MiniWob++. Additionally, our experiments highlight data scaling as a key driver for improving web agent capabilities. We hope this study makes state-of-the-art LMM-based agent research at a larger scale more accessible.

[Arxiv](https://arxiv.org/abs/2502.11357)