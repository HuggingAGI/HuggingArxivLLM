# 大型语言模型在 IT 自动化任务中的应用：我们真的准备好了吗？

发布时间：2025年05月26日

`LLM应用` `IT自动化` `代码生成`

> Large Language Models for IT Automation Tasks: Are We There Yet?

# 摘要

> 大型语言模型（LLMs）在代码生成领域潜力无限，但其在IT自动化任务中的表现，尤其是针对Ansible等工具的应用，仍存在较大研究空白。现有基准测试主要依赖无法准确反映实际需求的合成任务。为此，我们推出了ITAB（IT自动化任务基准），包含126个多样化任务（如服务器配置、文件管理等），每个任务均涉及状态协调这一IT自动化工具的独特属性。ITAB通过在受控环境中动态执行，评估LLMs生成功能化Ansible自动化脚本的能力。我们对14个开源LLMs进行了全面评估，但无一能实现12%以上的pass@10通过率。通过对1,411次执行失败案例的深入分析，我们发现两类主要语义错误：一是与状态协调相关的推理失败（变量、主机、路径和模板问题分别占11.43%、11.84%、11.63%和9.97%，总计44.87%），二是模块特定执行知识的不足（属性和参数、模块错误分别占14.44%和9.93%，总计24.37%）。研究结果揭示了开源LLMs在追踪状态变化和应用专用模块知识方面的关键局限性，表明可靠IT自动化需要在状态推理和领域特定执行理解方面取得重大突破。

> LLMs show promise in code generation, yet their effectiveness for IT automation tasks, particularly for tools like Ansible, remains understudied. Existing benchmarks rely primarily on synthetic tasks that fail to capture the needs of practitioners who use IT automation tools, such as Ansible. We present ITAB (IT Automation Task Benchmark), a benchmark of 126 diverse tasks (e.g., configuring servers, managing files) where each task accounts for state reconciliation: a property unique to IT automation tools. ITAB evaluates LLMs' ability to generate functional Ansible automation scripts via dynamic execution in controlled environments. We evaluate 14 open-source LLMs, none of which accomplish pass@10 at a rate beyond 12%. To explain these low scores, we analyze 1,411 execution failures across the evaluated LLMs and identify two main categories of prevalent semantic errors: failures in state reconciliation related reasoning (44.87% combined from variable (11.43%), host (11.84%), path(11.63%), and template (9.97%) issues) and deficiencies in module-specific execution knowledge (24.37% combined from Attribute and parameter (14.44%) and module (9.93%) errors). Our findings reveal key limitations in open-source LLMs' ability to track state changes and apply specialized module knowledge, indicating that reliable IT automation will require major advances in state reasoning and domain-specific execution understanding.

[Arxiv](https://arxiv.org/abs/2505.20505)