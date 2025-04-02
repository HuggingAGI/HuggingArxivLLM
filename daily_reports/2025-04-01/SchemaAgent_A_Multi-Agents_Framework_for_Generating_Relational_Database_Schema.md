# SchemaAgent：一个生成关系型数据库模式的多智能体系统
发布时间：2025年03月31日

`代码编写`
> SchemaAgent: A Multi-Agents Framework for Generating Relational Database Schema
>
> 关系型数据库设计根据用户需求生成架构，定义表结构及其相互关系。从需求到架构的准确转化涉及多个复杂子任务，需要数据库专业知识和特定领域知识。这对关系型数据库的自动化设计提出了独特挑战。现有方法多基于定制规则或传统深度学习模型，生成的架构往往不够理想。最近，大型语言模型（LLMs）在智能应用开发方面取得了显著进展。本文提出SchemaAgent，一个基于LLM的统一多智能体框架，用于自动生成高质量数据库架构。SchemaAgent首次将LLMs应用于架构生成，通过为智能体分配专门角色并促进协作，模拟手动设计流程以优化子任务。架构生成流程中，直接应用多智能体框架可能导致错误累积。为此，我们引入反思和检查角色，并设计创新的错误检测与纠正机制，跨阶段识别并修复问题。为评估，我们构建了包含500多对需求描述与架构的	extit{RSchema}基准。实验结果表明，与主流LLMs相比，SchemaAgent在关系型数据库架构生成方面具有显著优势。
>
> https://arxiv.org/abs/2503.23886

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23886](https://arxiv.org/abs/2503.23886)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)