# # SPOT：为调查记者搭建自然语言与地理空间搜索之间的桥梁

发布时间：2025年06月16日

`LLM应用` `调查 journalism` `新闻业`

> SPOT: Bridging Natural Language and Geospatial Search for Investigative Journalists

# 摘要

> OpenStreetMap (OSM) 是调查记者进行地理定位验证的不可或缺的资源。然而，现有的工具如 Overpass Turbo 需要复杂的查询语言，为非技术人员设置了使用门槛。为此，我们推出了 SPOT，一个开源的自然语言界面，通过直观的场景描述，让 OSM 的地理数据更加易于访问。SPOT 利用微调的大型语言模型 (LLMs) 将用户输入转化为地理空间对象的结构化表示，并通过交互式地图界面呈现结果。虽然通用的地理空间搜索任务是可行的，但 SPOT 特别针对调查 journalism 场景设计，旨在解决模型输出幻觉、OSM 标签不一致以及用户输入噪声等现实挑战。它结合了新颖的合成数据管道和语义捆绑系统，以实现强大且精准的查询生成。据我们所知，SPOT 是首个在这一精度水平上实现对 OSM 数据可靠自然语言访问的系统。通过降低技术门槛，SPOT 为事实核查和打击虚假信息提供了实用工具，助力更广泛的努力。

> OpenStreetMap (OSM) is a vital resource for investigative journalists doing geolocation verification. However, existing tools to query OSM data such as Overpass Turbo require familiarity with complex query languages, creating barriers for non-technical users. We present SPOT, an open source natural language interface that makes OSM's rich, tag-based geographic data more accessible through intuitive scene descriptions. SPOT interprets user inputs as structured representations of geospatial object configurations using fine-tuned Large Language Models (LLMs), with results being displayed in an interactive map interface. While more general geospatial search tasks are conceivable, SPOT is specifically designed for use in investigative journalism, addressing real-world challenges such as hallucinations in model output, inconsistencies in OSM tagging, and the noisy nature of user input. It combines a novel synthetic data pipeline with a semantic bundling system to enable robust, accurate query generation. To our knowledge, SPOT is the first system to achieve reliable natural language access to OSM data at this level of accuracy. By lowering the technical barrier to geolocation verification, SPOT contributes a practical tool to the broader efforts to support fact-checking and combat disinformation.

[Arxiv](https://arxiv.org/abs/2506.13188)