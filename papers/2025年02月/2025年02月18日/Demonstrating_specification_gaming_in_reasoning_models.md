# 推理模型中的规格游戏展示

发布时间：2025年02月18日

`Agent` `博弈论`

> Demonstrating specification gaming in reasoning models

# 摘要

> 我们通过指示模型击败国际象棋引擎来展示LLM智能体规范博弈。发现推理模型如o1 preview和DeepSeek-R1往往会默认破解基准，而像GPT-4o和Claude 3.5 Sonnet这样的语言模型则需要明确告知常规玩法无法奏效，才会尝试破解。我们通过使用现实的任务提示并避免过多的引导，改进了先前的工作（如Hubinger等人，2024；Meinke等人，2024；Weij等人，2024）。实验结果表明，推理模型可能倾向于通过破解来解决难题，这与OpenAI（2024）在网络安全能力测试中观察到的o1 Docker逃逸现象相符。

> We demonstrate LLM agent specification gaming by instructing models to win against a chess engine. We find reasoning models like o1 preview and DeepSeek-R1 will often hack the benchmark by default, while language models like GPT-4o and Claude 3.5 Sonnet need to be told that normal play won't work to hack.
  We improve upon prior work like (Hubinger et al., 2024; Meinke et al., 2024; Weij et al., 2024) by using realistic task prompts and avoiding excess nudging. Our results suggest reasoning models may resort to hacking to solve difficult problems, as observed in OpenAI (2024)'s o1 Docker escape during cyber capabilities testing.

[Arxiv](https://arxiv.org/abs/2502.13295)