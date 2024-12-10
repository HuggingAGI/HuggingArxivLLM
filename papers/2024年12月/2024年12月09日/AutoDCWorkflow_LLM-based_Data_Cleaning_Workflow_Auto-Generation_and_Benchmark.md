# AutoDCWorkflow：基于 LLM 的数据清洗工作流自动生成及基准

发布时间：2024年12月09日

`LLM应用` `数据清理` `语言模型`

> AutoDCWorkflow: LLM-based Data Cleaning Workflow Auto-Generation and Benchmark

# 摘要

> 我们对大型语言模型（LLMs）自动生成数据清理工作流的推理能力展开研究。为评估LLMs完成数据清理任务的能力，我们为基于LLM的自动数据清理工作流（AutoDCWorkflow）搭建了一个管道，引导LLMs进行数据清理操作，来修复三类数据质量问题：重复、缺失值以及不一致的数据格式。给定一张脏表和一个目的（以查询形式呈现），此管道会生成一张能满足目的的最小干净表，以及用于生成该表的数据清理工作流。规划过程涵盖三个主要的LLM驱动组件：（1）选择目标列：确定与目的相关的一组目标列。（2）检查列质量：评估每个目标列的数据质量，并生成数据质量报告作为操作目标。（3）生成操作和参数：依据数据质量报告结果预测下一个操作及参数。另外，我们提出了一个数据清理基准，用于评估LLM代理自动生成能解决不同难度级别数据清理目的工作流的能力。该基准包含带注释的数据集，即目的、原始表、干净表、数据清理工作流和答案集的集合。在我们的实验中，评估了三个能自动生成目的驱动的数据清理工作流的LLMs。结果显示，LLMs在规划和生成数据清理工作流方面表现出色，无需微调。

> We investigate the reasoning capabilities of large language models (LLMs) for automatically generating data-cleaning workflows. To evaluate LLMs' ability to complete data-cleaning tasks, we implemented a pipeline for LLM-based Auto Data Cleaning Workflow (AutoDCWorkflow), prompting LLMs on data cleaning operations to repair three types of data quality issues: duplicates, missing values, and inconsistent data formats. Given a dirty table and a purpose (expressed as a query), this pipeline generates a minimal, clean table sufficient to address the purpose and the data cleaning workflow used to produce the table. The planning process involves three main LLM-driven components: (1) Select Target Columns: Identifies a set of target columns related to the purpose. (2) Inspect Column Quality: Assesses the data quality for each target column and generates a Data Quality Report as operation objectives. (3) Generate Operation & Arguments: Predicts the next operation and arguments based on the data quality report results. Additionally, we propose a data cleaning benchmark to evaluate the capability of LLM agents to automatically generate workflows that address data cleaning purposes of varying difficulty levels. The benchmark comprises the annotated datasets as a collection of purpose, raw table, clean table, data cleaning workflow, and answer set. In our experiments, we evaluated three LLMs that auto-generate purpose-driven data cleaning workflows. The results indicate that LLMs perform well in planning and generating data-cleaning workflows without the need for fine-tuning.

[Arxiv](https://arxiv.org/abs/2412.06724)