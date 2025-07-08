# 以消歧为核心的微调让企业级工具调用大模型更实用更安全

发布时间：2025年07月04日

`LLM应用` `企业级应用` `API调用`

> Disambiguation-Centric Finetuning Makes Enterprise Tool-Calling LLMs More Realistic and Less Risky

# 摘要

> 大型语言模型（LLMs）在调用企业API时面临挑战：当近似工具争夺同一用户意图，或参数未充分指定时，模型往往表现不佳。为此，我们推出以消歧为核心的DiaFORGE框架，包含三个关键阶段：生成基于角色的多轮对话，助手需在相似工具间精准区分；对开源模型进行参数范围从30亿到700亿的监督微调，保留推理轨迹；通过动态评估套件，在实时智能体循环中重新部署模型，全面衡量端到端目标完成度和传统静态指标。在DiaBENCH基准测试中，使用DiaFORGE训练的模型在优化提示下，工具调用成功率较GPT-4o提升27个百分点，较Claude-3.5-Sonnet提升49个百分点。为促进研究，我们开源了5000个企业级API规范，配以严格验证的消歧对话，为构建可靠的企业级工具调用代理提供实用指南。


> Large language models (LLMs) are increasingly tasked with invoking enterprise APIs, yet they routinely falter when near-duplicate tools vie for the same user intent or when required arguments are left underspecified. We introduce DiaFORGE (Dialogue Framework for Organic Response Generation & Evaluation), a disambiguation-centric, three-stage pipeline that (i) synthesizes persona-driven, multi-turn dialogues in which the assistant must distinguish among highly similar tools, (ii) performs supervised fine-tuning of open-source models with reasoning traces across 3B - 70B parameters, and (iii) evaluates real-world readiness via a dynamic suite that redeploys each model in a live agentic loop and reports end-to-end goal completion alongside conventional static metrics. On our dynamic benchmark DiaBENCH, models trained with DiaFORGE raise tool-invocation success by 27 pp over GPT-4o and by 49 pp over Claude-3.5-Sonnet, both under optimized prompting. To spur further research, we release an open corpus of 5000 production-grade enterprise API specifications paired with rigorously validated, disambiguation-focused dialogues, offering a practical blueprint for building reliable, enterprise-ready tool-calling agents.

[Arxiv](https://arxiv.org/abs/2507.03336)