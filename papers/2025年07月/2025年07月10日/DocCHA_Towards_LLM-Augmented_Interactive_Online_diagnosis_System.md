# DocCHA: 面向增强型交互式在线诊断系统的 LLM 应用探索

发布时间：2025年07月10日

`LLM应用` `对话系统`

> DocCHA: Towards LLM-Augmented Interactive Online diagnosis System

# 摘要

> 尽管大型语言模型（LLMs）表现出色，现有的对话式医疗代理（CHAs）仍显静态且脆弱，缺乏自适应多轮推理、症状澄清及透明决策能力。这严重限制了它们在临床诊断中的实际应用，因为诊断过程需要迭代且结构化的对话。为此，我们提出了DocCHA，一个基于信心感知的模块化框架，通过将诊断过程分解为三个阶段来模拟临床推理：（1）症状提取，（2）病史采集，（3）因果图构建。每个模块利用可解释的信心分数，指导自适应提问，优先进行信息澄清，并完善推理链。在IMCS21和DX两个真实中文咨询数据集上，DocCHA的表现优于GPT-3.5、GPT-4o和LLaMA-3等强大的基于提示的LLM基线，诊断准确率提升了5.18个百分点，症状召回率提升了30%以上，仅小幅增加了对话轮数。这些结果充分证明了DocCHA在实现结构化、透明且高效诊断对话方面的有效性，为多语言和资源受限环境下开发值得信赖的LLM驱动临床助手奠定了坚实基础。

> Despite the impressive capabilities of Large Language Models (LLMs), existing Conversational Health Agents (CHAs) remain static and brittle, incapable of adaptive multi-turn reasoning, symptom clarification, or transparent decision-making. This hinders their real-world applicability in clinical diagnosis, where iterative and structured dialogue is essential. We propose DocCHA, a confidence-aware, modular framework that emulates clinical reasoning by decomposing the diagnostic process into three stages: (1) symptom elicitation, (2) history acquisition, and (3) causal graph construction. Each module uses interpretable confidence scores to guide adaptive questioning, prioritize informative clarifications, and refine weak reasoning links.
  Evaluated on two real-world Chinese consultation datasets (IMCS21, DX), DocCHA consistently outperforms strong prompting-based LLM baselines (GPT-3.5, GPT-4o, LLaMA-3), achieving up to 5.18 percent higher diagnostic accuracy and over 30 percent improvement in symptom recall, with only modest increase in dialogue turns. These results demonstrate the effectiveness of DocCHA in enabling structured, transparent, and efficient diagnostic conversations -- paving the way for trustworthy LLM-powered clinical assistants in multilingual and resource-constrained settings.

[Arxiv](https://arxiv.org/abs/2507.07870)