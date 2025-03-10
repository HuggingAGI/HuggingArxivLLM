# 你的LLM文本到SQL模型安全吗？通过后门攻击探索SQL注入威胁
发布时间：2025年03月07日

`代码编写`
> Are Your LLM-based Text-to-SQL Models Secure? Exploring SQL Injection via Backdoor Attacks
>
> 大型语言模型（LLMs）在文本到SQL转换任务中展现了顶尖水平的结果，然而这一长期困扰数据库领域的挑战背后，安全问题尤其是后门攻击的威胁仍未得到充分探索。本研究系统性地调查了基于LLM的Text-to-SQL模型的漏洞，提出了ToxicSQL这一新颖的后门攻击框架。我们采用隐蔽的语义和字符级触发器，使后门难以被检测和移除，同时确保恶意行为隐秘，模型在良性输入上仍保持高准确性。我们创新性地利用SQL注入载荷作为后门目标，生成恶意但可执行的SQL查询，对基于语言模型的SQL开发带来严重安全和隐私风险。实验表明，仅需0.44%的中毒数据即可实现79.41%的攻击成功率，对数据库安全构成重大威胁。此外，我们提出了检测和缓解策略以增强模型可靠性。本研究强调了在Text-to-SQL开发中重视安全性的紧迫性，并突显了构建强健防御以抵御后门威胁的重要性。
>
> https://arxiv.org/abs/2503.05445

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.05445](https://arxiv.org/abs/2503.05445)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)