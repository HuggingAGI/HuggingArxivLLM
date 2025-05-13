# Byam：借助大型语言模型修复破坏性依赖更新

发布时间：2025年05月12日

`LLM应用` `软件工程` `人工智能`

> Byam: Fixing Breaking Dependency Updates with Large Language Models

# 摘要

> API简化了第三方依赖在客户端代码中的集成。但API的更改，如弃用、参数调整或替换，常会导致客户端代码失效，这被称为破坏性依赖更新。识别这些破坏并修复代码对开发者来说往往耗时费力。本文提出利用大型语言模型（LLMs）自动修复破坏性依赖更新。我们在Java项目的BUMP基准数据集上验证了这一方法。我们的方法结合了LLMs与高级提示，整合了构建过程和依赖分析的信息。我们从构建、文件和单个编译错误三个层次评估效果。实验中使用了Google Gemini-2.0 Flash、OpenAI GPT4o-mini、OpenAI o3-mini、Alibaba Qwen2.5-32b-instruct 和 DeepSeek V3五种模型。结果显示，LLMs能有效修复破坏性更新。其中，OpenAI的o3-mini表现最佳，使用包含错误行、API差异、错误信息和推理指令的提示时，能修复27%的构建和78%的编译错误。这表明，LLMs有潜力帮助开发者自动修复依赖更新引发的编译错误。

> Application Programming Interfaces (APIs) facilitate the integration of third-party dependencies within the code of client applications. However, changes to an API, such as deprecation, modification of parameter names or types, or complete replacement with a new API, can break existing client code. These changes are called breaking dependency updates; It is often tedious for API users to identify the cause of these breaks and update their code accordingly. In this paper, we explore the use of Large Language Models (LLMs) to automate client code updates in response to breaking dependency updates. We evaluate our approach on the BUMP dataset, a benchmark for breaking dependency updates in Java projects. Our approach leverages LLMs with advanced prompts, including information from the build process and from the breaking dependency analysis. We assess effectiveness at three granularity levels: at the build level, the file level, and the individual compilation error level. We experiment with five LLMs: Google Gemini-2.0 Flash, OpenAI GPT4o-mini, OpenAI o3-mini, Alibaba Qwen2.5-32b-instruct, and DeepSeek V3. Our results show that LLMs can automatically repair breaking updates. Among the considered models, OpenAI's o3-mini is the best, able to completely fix 27% of the builds when using prompts that include contextual information such as the buggy line, API differences, error messages, and step-by-step reasoning instructions. Also, it fixes 78% of the individual compilation errors. Overall, our findings demonstrate the potential for LLMs to fix compilation errors due to breaking dependency updates, supporting developers in their efforts to stay up-to-date with changes in their dependencies.

[Arxiv](https://arxiv.org/abs/2505.07522)