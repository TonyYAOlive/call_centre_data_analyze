## Customer Support Behavior Analysis

This project analyzes historical call center data to understand customer behavior and operational preformance, with a focus on identifying early churn risks.

The insights are intended to support day-to-day operational decisions and longer-term retention strategies.

## Business Context

随着用户规模增长，客服通话量持续上升，管理层希望了解：
- 当前通话需求是否出现异常变化
- 客户问题是否得到有效解
- 是否存在可提前干预的流失风险

## Existing Setup (Before My Involvement)

在我加入项目之前，客服中心已具备以下基础分析与监控能力：

- 基础通话量、平均通话时长（AHT）等运营指标
- 日级通话量监控报表
- 简单的异常告警规则（基于固定阈值）

## My Focus & Contributions

在现有基础上，我主要聚焦于以下问题：

- 将监控从「单一指标」扩展为「行为与结果结合」
- 分析通话行为与客户流失之间的关系
- 识别高风险客户群体，为运营提供提前干预依据

## Analysis Scope

本项目拆分为 4 个核心分析模块（Analysis Units）：

- **AU-01** 通话量趋势与异常分析
- **AU-02** 来电类型与客户流失关系
- **AU-03** 高频未解决来电客户识别
- **AU-04** 坐席绩效与排班效率分析

## Key Insights

1. 账单相关来电在新收费规则上线后显著增加（+32%）。
2. 高频且未解决来电是客户流失的重要先行信号。
3. 晚高峰时段人力配置不足，影响整体服务效率。

## Recommendations

- 提前发布账单相关指引，减少咨询压力。
- 建立高风险客户预警规则，优先介入。
- 优化晚高峰坐席排班配置。

## Project Structure

call-center-analysis/
├── sql/        # 指标计算与分析查询
├── notebooks/  # EDA 与行为分析 过程
├── dashboard/  # Tableau / Power BI 可视化

├── docs # 结论性

└── README.md