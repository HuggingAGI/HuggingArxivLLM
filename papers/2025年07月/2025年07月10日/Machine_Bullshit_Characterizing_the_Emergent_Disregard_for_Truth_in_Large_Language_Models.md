# 机器人的胡言乱语：解析大型语言模型中对真相的日益漠视现象

发布时间：2025年07月10日

`LLM理论

LLM理论` `AI伦理`

> Machine Bullshit: Characterizing the Emergent Disregard for Truth in Large Language Models

# 摘要

> 哲学家Harry Frankfurt所定义的“ bullshit”（胡说八道），指的是不考虑其真实性的言论。尽管之前的研究已经探讨了大型语言模型（LLM）的幻觉和奉承现象，但我们提出“机器 bullshit”作为一个高层次的概念框架，使研究人员能够更全面地描述LLMs中出现的真实性的丧失现象，并揭示其背后的机制。我们引入了“胡说八道指数”（Bullshit Index），这是一个量化LLMs对真理漠不关心程度的新指标，并提出了一种补充分类法，分析四种 bullshit 的定性形式：空洞的言辞、虚伪的敷衍、含糊其辞和未经验证的主张。我们在Marketplace数据集、Political Neutrality数据集以及我们新设计的BullshitEval基准数据集（涵盖100种AI助手的2,400种场景）上进行了实证评估，该基准数据集专门用于评估机器 bullshit。我们的结果显示，通过基于人类反馈的强化学习（RLHF）对模型进行微调会显著加剧 bullshit，并且推理时的思维链（CoT）提示会显著放大特定的 bullshit 形式，尤其是空洞的言辞和虚伪的敷衍。我们还观察到在政治语境中普遍存在机器 bullshit，其中含糊其辞是最主要的策略。我们的研究发现突显了AI对齐系统性挑战，并为实现更真实的LLM行为提供了新的见解。


> Bullshit, as conceptualized by philosopher Harry Frankfurt, refers to statements made without regard to their truth value. While previous work has explored large language model (LLM) hallucination and sycophancy, we propose machine bullshit as an overarching conceptual framework that can allow researchers to characterize the broader phenomenon of emergent loss of truthfulness in LLMs and shed light on its underlying mechanisms. We introduce the Bullshit Index, a novel metric quantifying LLMs' indifference to truth, and propose a complementary taxonomy analyzing four qualitative forms of bullshit: empty rhetoric, paltering, weasel words, and unverified claims. We conduct empirical evaluations on the Marketplace dataset, the Political Neutrality dataset, and our new BullshitEval benchmark (2,400 scenarios spanning 100 AI assistants) explicitly designed to evaluate machine bullshit. Our results demonstrate that model fine-tuning with reinforcement learning from human feedback (RLHF) significantly exacerbates bullshit and inference-time chain-of-thought (CoT) prompting notably amplify specific bullshit forms, particularly empty rhetoric and paltering. We also observe prevalent machine bullshit in political contexts, with weasel words as the dominant strategy. Our findings highlight systematic challenges in AI alignment and provide new insights toward more truthful LLM behavior.

[Arxiv](https://arxiv.org/abs/2507.07484)