# SLIP：基于软标签机制和关键信息提取引导的CoT防御，针对API中的指令后门

发布时间：2025年08月08日

`LLM应用

理由：这篇论文讨论了针对大型语言模型（LLM）的后门攻击及其防御机制，属于LLM的应用领域，特别是安全应用。`

> SLIP: Soft Label Mechanism and Key-Extraction-Guided CoT-based Defense Against Instruction Backdoor in APIs

# 摘要

> 随着定制化大型语言模型（LLM）代理的发展，一种新的黑盒后门攻击威胁浮现，攻击者将恶意指令注入隐藏的系统提示中。这些攻击轻易绕过了依赖白盒访问的现有防御机制，带来了严重的安全挑战。针对这一问题，我们提出了SLIP，这是一种基于软标签机制和关键信息提取引导的CoT方法，用于防御API中的指令后门攻击。SLIP的设计基于两个关键洞察：首先，为了解决不法触发词对模型的过度敏感问题，我们提出了基于关键信息提取的思维链（KCoT）。不同于仅关注单一触发词或输入句子，KCoT引导代理提取与任务相关的关键词组。其次，为了引导LLM走向正确答案，我们提出的软标签机制（SLM）引导代理量化关键词组与候选答案之间的语义关联性。关键的是，为了减轻KCoT提取短语中残留触发词或误导内容的影响，通常会导致异常分数，SLM排除了显著偏离均值的异常分数，并随后对剩余分数进行平均以获得更可靠的语义表示。在分类和问答（QA）任务上的大量实验表明，SLIP非常有效，将平均攻击成功率（ASR）从90.2%降低到25.13%，同时在干净数据上保持高准确率，并超越了现有的最先进的防御方法。我们的代码可在https://github.com/CAU-ISS-Lab/Backdoor-Attack-Defense-LLMs/tree/main/SLIP获取。

> With the development of customized large language model (LLM) agents, a new threat of black-box backdoor attacks has emerged, where malicious instructions are injected into hidden system prompts. These attacks easily bypass existing defenses that rely on white-box access, posing a serious security challenge. To address this, we propose SLIP, a Soft Label mechanism and key-extraction-guided CoT-based defense against Instruction backdoors in APIs. SLIP is designed based on two key insights. First, to counteract the model's oversensitivity to triggers, we propose a Key-extraction-guided Chain-of-Thought (KCoT). Instead of only considering the single trigger or the input sentence, KCoT prompts the agent to extract task-relevant key phrases. Second, to guide the LLM toward correct answers, our proposed Soft Label Mechanism (SLM) prompts the agent to quantify the semantic correlation between key phrases and candidate answers. Crucially, to mitigate the influence of residual triggers or misleading content in phrases extracted by KCoT, which typically causes anomalous scores, SLM excludes anomalous scores deviating significantly from the mean and subsequently averages the remaining scores to derive a more reliable semantic representation. Extensive experiments on classification and question-answer (QA) tasks demonstrate that SLIP is highly effective, reducing the average attack success rate (ASR) from 90.2% to 25.13% while maintaining high accuracy on clean data and outperforming state-of-the-art defenses. Our code are available in https://github.com/CAU-ISS-Lab/Backdoor-Attack-Defense-LLMs/tree/main/SLIP.

[Arxiv](https://arxiv.org/abs/2508.06153)