# MM-DREX：面向金融交易的多模态驱动LLM专家动态路由

发布时间：2025年09月05日

`Agent` `金融科技`

> MM-DREX: Multimodal-Driven Dynamic Routing of LLM Experts for Financial Trading

# 摘要

> 金融市场固有的非平稳性与多模态信息的复杂性，给现有量化交易模型带来了严峻挑战。传统方法依赖固定结构与单模态数据，难以适应市场状态转换；而大型语言模型（LLM）驱动的解决方案虽具备多模态理解能力，却受限于静态策略与同质化专家设计，缺乏动态调整及细粒度决策机制。为应对这些局限，我们提出MM-DREX：一个基于大型语言模型的多模态驱动、动态路由专家框架。该框架明确将市场状态感知与策略执行解耦，从而在非平稳环境中实现自适应序贯决策。具体而言，它（1）引入视觉语言模型（VLM）驱动的动态路由器，通过联合分析K线图模式与长期时间特征，实现实时专家权重分配；（2）设计四类异构交易专家（趋势、反转、突破、定位），生成专业化的细粒度子策略；（3）提出SFT-RL混合训练范式，协同优化路由器的市场分类能力与专家的风险调整决策。在涵盖股票、期货和加密货币的多模态数据集上开展的大量实验显示，MM-DREX在总回报率、夏普比率、最大回撤等关键指标上显著优于15个基线模型（包括最先进的金融LLM和深度强化学习模型），充分验证了其稳健性与泛化能力。此外，可解释性模块实时追踪路由逻辑与专家行为，为策略透明度提供审计依据。

> The inherent non-stationarity of financial markets and the complexity of multi-modal information pose significant challenges to existing quantitative trading models. Traditional methods relying on fixed structures and unimodal data struggle to adapt to market regime shifts, while large language model (LLM)-driven solutions - despite their multi-modal comprehension - suffer from static strategies and homogeneous expert designs, lacking dynamic adjustment and fine-grained decision mechanisms. To address these limitations, we propose MM-DREX: a Multimodal-driven, Dynamically-Routed EXpert framework based on large language models. MM-DREX explicitly decouples market state perception from strategy execution to enable adaptive sequential decision-making in non-stationary environments. Specifically, it (1) introduces a vision-language model (VLM)-powered dynamic router that jointly analyzes candlestick chart patterns and long-term temporal features to allocate real-time expert weights; (2) designs four heterogeneous trading experts (trend, reversal, breakout, positioning) generating specialized fine-grained sub-strategies; and (3) proposes an SFT-RL hybrid training paradigm to synergistically optimize the router's market classification capability and experts' risk-adjusted decision-making. Extensive experiments on multi-modal datasets spanning stocks, futures, and cryptocurrencies demonstrate that MM-DREX significantly outperforms 15 baselines (including state-of-the-art financial LLMs and deep reinforcement learning models) across key metrics: total return, Sharpe ratio, and maximum drawdown, validating its robustness and generalization. Additionally, an interpretability module traces routing logic and expert behavior in real time, providing an audit trail for strategy transparency.

[Arxiv](https://arxiv.org/abs/2509.05080)