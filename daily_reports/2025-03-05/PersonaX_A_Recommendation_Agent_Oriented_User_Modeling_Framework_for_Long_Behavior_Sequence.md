# PersonaX: 长行为序列用户建模框架，专为推荐代理设计
发布时间：2025年03月04日


> PersonaX: A Recommendation Agent Oriented User Modeling Framework for Long Behavior Sequence
>
> 推荐代理借助大型语言模型（LLM）进行用户建模（UM），构建文本化人设以实现与真实用户的精准对齐。然而，现有LLM UM方法在处理长篇用户生成内容（UGC）时面临上下文限制和性能下降的挑战。尽管通常会采用基于相关性或时间顺序的采样策略，但这些方法不可避免地忽略了被丢弃行为中蕴含的多样化用户兴趣，导致用户建模不完整，用户画像质量下降。此外，基于相关性的采样需要实时检索，迫使用户建模过程在线运行，从而引入了显著的延迟开销。为解决这些问题，我们提出了PersonaX——一个与代理无关的LLM UM框架，通过子行为序列（SBS）选择和离线多个人设构建来应对挑战。PersonaX离线提取紧凑的SBS片段，捕捉多样化的用户兴趣，生成精细的文本化人设并缓存，以实现高效的在线检索。这种方法确保用于提示的用户人设始终与当前上下文高度相关，同时消除了在线用户建模的需要。在SBS选择中，我们通过平衡采样数据中的原型性和多样性，确保了效率（长度小于五个）和高代表性质量。大量实验验证了PersonaX在高质量用户画像中的有效性与 versatility。仅使用30%到50%的行为数据，序列长度为480，将PersonaX与AgentCF集成可带来3%到11%的绝对性能提升，而与Agent4Rec集成则可实现10%到50%的性能提升。作为与代理无关的框架，PersonaX为可扩展的用户建模设立了新基准，为更准确和高效的LLM驱动推荐代理铺平了道路。
>
> https://arxiv.org/abs/2503.02398

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.02398](https://arxiv.org/abs/2503.02398)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)