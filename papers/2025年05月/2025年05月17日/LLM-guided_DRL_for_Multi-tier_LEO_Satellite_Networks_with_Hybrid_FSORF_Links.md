# 基于LLM的DRL在多层低轨卫星网络中的应用，采用混合FSO/RF链路

发布时间：2025年05月17日

`LLM应用` `卫星通信` `网络架构`

> LLM-guided DRL for Multi-tier LEO Satellite Networks with Hybrid FSO/RF Links

# 摘要

> 地面网络尽管取得了显著进展，但为偏远地区提供可靠覆盖以及在自然灾害期间保持网络韧性仍面临固有挑战。基于低地球轨道卫星和高空气平台的多层网络架构提供了有前景的解决方案，但面临着由高移动性和动态信道条件引发的连接不稳定和频繁切换问题。本文设计了一种融合自由空间光通信和射频链路的三层网络架构，集成低地球轨道卫星、高空气平台和地面终端，旨在最大化覆盖范围同时保障连接可靠性。该混合架构利用自由空间光通信的高带宽优势实现卫星到高空气平台的链路，同时借助射频通信的抗天气干扰特性实现高空气平台到地面终端的链路。我们提出了一种联合优化问题，通过优化网络配置和卫星切换决策，在下行传输速率和切换频率之间取得平衡。该问题具有高度动态性和非凸性，且存在时间耦合约束。为应对这些挑战，我们提出了一种创新的LLM引导截断分位数批评算法，结合动态动作遮罩技术，利用LLM自适应调节超参数以消除不必要的探索。仿真结果表明，所提出的LTQC-DAM算法在收敛速度、下行传输速率和切换频率等方面均优于基准算法。此外，我们发现与其他先进LLM相比，DeepSeek通过渐进式、语境感知的参数调整实现了最佳性能表现。

> Despite significant advancements in terrestrial networks, inherent limitations persist in providing reliable coverage to remote areas and maintaining resilience during natural disasters. Multi-tier networks with low Earth orbit (LEO) satellites and high-altitude platforms (HAPs) offer promising solutions, but face challenges from high mobility and dynamic channel conditions that cause unstable connections and frequent handovers. In this paper, we design a three-tier network architecture that integrates LEO satellites, HAPs, and ground terminals with hybrid free-space optical (FSO) and radio frequency (RF) links to maximize coverage while maintaining connectivity reliability. This hybrid approach leverages the high bandwidth of FSO for satellite-to-HAP links and the weather resilience of RF for HAP-to-ground links. We formulate a joint optimization problem to simultaneously balance downlink transmission rate and handover frequency by optimizing network configuration and satellite handover decisions. The problem is highly dynamic and non-convex with time-coupled constraints. To address these challenges, we propose a novel large language model (LLM)-guided truncated quantile critics algorithm with dynamic action masking (LTQC-DAM) that utilizes dynamic action masking to eliminate unnecessary exploration and employs LLMs to adaptively tune hyperparameters. Simulation results demonstrate that the proposed LTQC-DAM algorithm outperforms baseline algorithms in terms of convergence, downlink transmission rate, and handover frequency. We also reveal that compared to other state-of-the-art LLMs, DeepSeek delivers the best performance through gradual, contextually-aware parameter adjustments.

[Arxiv](https://arxiv.org/abs/2505.11978)