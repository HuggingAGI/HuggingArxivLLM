# # LLM 能力与路由数据的融合

发布时间：2025年07月14日

`LLM应用` `跨领域` `人工智能`

> Fusing LLM Capabilities with Routing Data

# 摘要

> 大型语言模型（LLMs）的快速发展催生了一个充满活力的生态系统，多样化的架构因设计、训练数据和目标的不同而各具特色。然而，大多数应用仍依赖单一后端模型，这不仅限制了能力覆盖范围，还在处理复杂任务时导致性能和令牌成本的低效。我们发现了一个未被充分探索的机会：LLM路由数据，即当托管平台将不同查询路由到不同模型时产生的数据，这些数据可以揭示模型在不同任务中的相对优势。

为了解决这一问题，我们提出了FusionBench，这是一个全面的路由基准，涵盖五个领域中的14项任务，涉及20个开源LLM（参数规模从8B到671B），捕获了1亿3千万个令牌，并从顶级模型中总结出可重用的思考模板。在此基础上，我们引入了FusionFactory，一个系统化的融合框架，包含三个层级：(1) 查询级融合，为每个查询定制路由器，结合直接响应和推理增强输出；(2) 思考级融合，利用从顶级LLM对类似查询的回答中提取的抽象模板；(3) 模型级融合，通过蒸馏在模型间转移能力，使用顶级响应或最高评委分数作为训练数据。

实验表明，FusionFactory在所有14个基准测试中始终优于最佳单个LLM，且最优融合配置因基准而异，这证明了系统化LLM融合在利用互补优势和提升整体性能方面的价值。

> The rapid advancement of large language models (LLMs) has created a vibrant ecosystem of diverse architectures, each with unique strengths due to differences in design, training data, and objectives. However, most applications still rely on a single backend model, limiting coverage of capabilities and leading to inefficiencies in performance and token cost when tackling complex tasks. We highlight an underexploited opportunity: LLM routing data, produced when hosting platforms route diverse queries to different models, which can reveal comparative strengths across tasks. To address this, we propose FusionBench, a comprehensive routing benchmark covering 14 tasks across five domains with 20 open-source LLMs (8B to 671B parameters), capturing 103M tokens and summarizing reusable thought templates from top models. Building on this, we introduce FusionFactory, a systematic fusion framework with three levels: (1) query-level fusion, tailoring routers for each query using both direct responses and reasoning-augmented outputs; (2) thought-level fusion, leveraging abstract templates derived from top-performing LLMs' answers to similar queries; and (3) model-level fusion, transferring capabilities between models via distillation, using top responses or highest judge scores as training data. Experiments show FusionFactory consistently outperforms the best individual LLM across all 14 benchmarks, with optimal fusion configurations varying by benchmark, demonstrating the value of systematic LLM fusion in harnessing complementary strengths and improving overall performance.

[Arxiv](https://arxiv.org/abs/2507.10540)