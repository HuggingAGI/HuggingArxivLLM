# o3-mini vs DeepSeek-R1：谁更安全？

发布时间：2025年01月31日

`LLM应用` `AI模型` `安全性评估`

> o3-mini vs DeepSeek-R1: Which One is Safer?

# 摘要

> DeepSeek-R1的出现标志着AI行业，尤其是大型语言模型领域的一个重大转折点。其在创意思考、代码生成、数学运算和自动化程序修复等任务中展现了卓越性能，且执行成本更为经济。然而，大型语言模型必须与安全性和人类价值观保持一致。DeepSeek-R1的强劲对手是OpenAI的o3-mini模型，该模型在性能、安全性和成本方面均有望树立高标准。在这份技术报告中，我们系统性地评估了DeepSeek-R1（70b版本）和OpenAI的o3-mini（beta版本）的安全级别。为此，我们采用了近期发布的自动化安全测试工具——ASTRAL。借助这一工具，我们在两个模型上自动且系统性地生成并执行了1,260个测试输入。在对两个模型的输出进行半自动化评估后，结果显示DeepSeek-R1产生了显著更多的不安全响应（12%），而OpenAI的o3-mini仅占1.2%。

> The irruption of DeepSeek-R1 constitutes a turning point for the AI industry in general and the LLMs in particular. Its capabilities have demonstrated outstanding performance in several tasks, including creative thinking, code generation, maths and automated program repair, at apparently lower execution cost. However, LLMs must adhere to an important qualitative property, i.e., their alignment with safety and human values. A clear competitor of DeepSeek-R1 is its American counterpart, OpenAI's o3-mini model, which is expected to set high standards in terms of performance, safety and cost. In this technical report, we systematically assess the safety level of both DeepSeek-R1 (70b version) and OpenAI's o3-mini (beta version). To this end, we make use of our recently released automated safety testing tool, named ASTRAL. By leveraging this tool, we automatically and systematically generated and executed 1,260 test inputs on both models. After conducting a semi-automated assessment of the outcomes provided by both LLMs, the results indicate that DeepSeek-R1 produces significantly more unsafe responses (12%) than OpenAI's o3-mini (1.2%).

[Arxiv](https://arxiv.org/abs/2501.18438)