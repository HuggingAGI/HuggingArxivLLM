# 你的LLM文本到SQL模型安全吗？通过后门攻击探索SQL注入威胁

发布时间：2025年03月07日

`LLM理论` `数据库`

> Are Your LLM-based Text-to-SQL Models Secure? Exploring SQL Injection via Backdoor Attacks

# 摘要

> 大型语言模型（LLMs）在文本到SQL转换任务中展现了顶尖水平的结果，然而这一长期困扰数据库领域的挑战背后，安全问题尤其是后门攻击的威胁仍未得到充分探索。本研究系统性地调查了基于LLM的Text-to-SQL模型的漏洞，提出了ToxicSQL这一新颖的后门攻击框架。我们采用隐蔽的语义和字符级触发器，使后门难以被检测和移除，同时确保恶意行为隐秘，模型在良性输入上仍保持高准确性。我们创新性地利用SQL注入载荷作为后门目标，生成恶意但可执行的SQL查询，对基于语言模型的SQL开发带来严重安全和隐私风险。实验表明，仅需0.44%的中毒数据即可实现79.41%的攻击成功率，对数据库安全构成重大威胁。此外，我们提出了检测和缓解策略以增强模型可靠性。本研究强调了在Text-to-SQL开发中重视安全性的紧迫性，并突显了构建强健防御以抵御后门威胁的重要性。

> Large language models (LLMs) have shown state-of-the-art results in translating natural language questions into SQL queries (Text-to-SQL), a long-standing challenge within the database community. However, security concerns remain largely unexplored, particularly the threat of backdoor attacks, which can introduce malicious behaviors into models through fine-tuning with poisoned datasets. In this work, we systematically investigate the vulnerabilities of LLM-based Text-to-SQL models and present ToxicSQL, a novel backdoor attack framework. Our approach leverages stealthy {semantic and character-level triggers} to make backdoors difficult to detect and remove, ensuring that malicious behaviors remain covert while maintaining high model accuracy on benign inputs. Furthermore, we propose leveraging SQL injection payloads as backdoor targets, enabling the generation of malicious yet executable SQL queries, which pose severe security and privacy risks in language model-based SQL development. We demonstrate that injecting only 0.44% of poisoned data can result in an attack success rate of 79.41%, posing a significant risk to database security. Additionally, we propose detection and mitigation strategies to enhance model reliability. Our findings highlight the urgent need for security-aware Text-to-SQL development, emphasizing the importance of robust defenses against backdoor threats.

[Arxiv](https://arxiv.org/abs/2503.05445)