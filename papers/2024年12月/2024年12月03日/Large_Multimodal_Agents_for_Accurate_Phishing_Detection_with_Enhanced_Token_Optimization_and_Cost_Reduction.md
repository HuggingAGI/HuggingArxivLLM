# 大型多模态代理用于实现准确的网络钓鱼检测，同时进行增强令牌优化并降低成本

发布时间：2024年12月03日

`Agent` `网络安全` `网络钓鱼检测`

> Large Multimodal Agents for Accurate Phishing Detection with Enhanced Token Optimization and Cost Reduction

# 摘要

> 随着复杂网络钓鱼攻击的增多，对高效且经济的检测方案的需求愈发迫切。本文研究了利用大型多模态代理，尤其是 Gemini 1.5 Flash 和 GPT-4o mini，通过 API 来分析 URL 和网页截图，以此规避训练和维护 AI 系统的繁杂性。我们的发现表明，整合这两类数据显著提升了检测性能，远超单独使用其中任何一类。然而，API 的使用会产生每次查询的费用，其取决于输入和输出令牌的数量。为应对此问题，我们提出了一种两层的智能体方法：起初，一个智能体评估 URL，若无法确定，第二个智能体则同时评估 URL 和截图。该方法不但保持了强劲的检测性能，还通过最大程度减少不必要的多输入查询大幅降低了 API 成本。成本分析显示，运用智能体方法，GPT-4o mini 每 100 美元能处理的网站数量约为多模态方法的 4.2 倍（107,440 对比 25,626），Gemini 1.5 Flash 能处理的网站数量约为 2.6 倍（2,232,142 对比 862,068）。这些发现凸显了智能体方法相较于多模态方法显著的经济优势，为那些期望借助先进的 AI 进行网络钓鱼检测同时控制开支的组织提供了可行的解决方案。

> With the rise of sophisticated phishing attacks, there is a growing need for effective and economical detection solutions. This paper explores the use of large multimodal agents, specifically Gemini 1.5 Flash and GPT-4o mini, to analyze both URLs and webpage screenshots via APIs, thus avoiding the complexities of training and maintaining AI systems. Our findings indicate that integrating these two data types substantially enhances detection performance over using either type alone. However, API usage incurs costs per query that depend on the number of input and output tokens. To address this, we propose a two-tiered agentic approach: initially, one agent assesses the URL, and if inconclusive, a second agent evaluates both the URL and the screenshot. This method not only maintains robust detection performance but also significantly reduces API costs by minimizing unnecessary multi-input queries. Cost analysis shows that with the agentic approach, GPT-4o mini can process about 4.2 times as many websites per $100 compared to the multimodal approach (107,440 vs. 25,626), and Gemini 1.5 Flash can process about 2.6 times more websites (2,232,142 vs. 862,068). These findings underscore the significant economic benefits of the agentic approach over the multimodal method, providing a viable solution for organizations aiming to leverage advanced AI for phishing detection while controlling expenses.

[Arxiv](https://arxiv.org/abs/2412.02301)