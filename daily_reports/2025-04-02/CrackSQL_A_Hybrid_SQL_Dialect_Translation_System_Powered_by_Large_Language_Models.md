# CrackSQL: 基于大型语言模型的混合 SQL 方言翻译系统
发布时间：2025年04月01日

`代码编写`
> CrackSQL: A Hybrid SQL Dialect Translation System Powered by Large Language Models
>
> 方言翻译在实现异构数据库系统间的无缝交互中发挥着关键作用。然而，不同方言（如PostgreSQL到MySQL）之间的SQL查询翻译仍面临挑战，主要源于句法差异和语义微妙变化。现有方法，包括手动重写、基于规则的系统和基于大语言模型（LLM）的技术，往往存在高维护成本（如需编写自定义规则）或结果不可靠（如LLM生成不存在的函数）的问题，尤其在处理复杂查询时表现不佳。本次演示中，我们推出CrackSQL——首个结合规则与LLM方法的混合SQL方言翻译系统，旨在突破这些限制。CrackSQL借助LLMs的适应性，大幅减少人工干预，同时通过基于功能的查询处理，将长复杂SQL分割处理，从而提升翻译准确性。为增强系统鲁棒性，CrackSQL采用了新型跨方言语法嵌入模型，实现精准语法对齐，并引入自适应局部到全局翻译策略，有效解决相互依赖的查询操作。CrackSQL支持三种翻译模式，并提供多样化的部署和访问选项，包括Web控制台界面、PyPI软件包以及命令行工具，助力其在各类现实场景中的广泛应用。
>
> https://arxiv.org/abs/2504.00882

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.00882](https://arxiv.org/abs/2504.00882)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)