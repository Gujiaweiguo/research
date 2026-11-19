# 中美商业地产商管研究计划 v2（2026-11-19 定稿）

## 目标
为 Jason 的商管系统/会员系统/AI agent（目标市场：中国）提供美国对标情报。

## 基线（一次性，分模块）
- M1 头部客户图谱：业主名单、体量（GLA/项目数）、物业类型、披露渠道锚点
- M2 运营管理模式：招商、营运、企划、物业、财务五条线（KPI/组织/流程）
- M3 系统格局：商管ERP、会员、POS、客流、停车、智能楼宇(IBMS)、数据BI
- M4 AI 变化与 agent 应用：系统厂商 AI 功能、业主侧落地案例、效果数据

## v2 新增范围（2026-11-19 Jason 指示）
- 客流：美国 Placer.ai/SmartAMT 类 vs 中国汇客云等；口径（到店/去重/途经）与商业用法
- 停车：美国外包模式（SP+/ABM 类）vs 中国停车集成进商管/会员（停车券核销联动）
- 智能楼宇 IBMS：美国独立 BMS（Johnson Controls/Honeywell/Siemens）vs 中国慧云式一体化集成；能耗/消防/安防数据与商管数据是否打通
- 三者与会员/营销/agent 的联动点（如客流×销售×停车数据的 agent 输入）

## 跟踪层（月度 cron，基线落地后挂）
cre-management-digest 四板块：①头部客户动态 ②供应商动向（含客流/停车/IBMS）③AI agent 落地案例与效果 ④产品对照点评

## 数据源（已验证）
- SEC EDGAR FTS / annualreports.com 镜像（10-K）
- 巨潮 fulltextSearch + static.cninfo.com.cn（A股/REIT）
- HKEX 披露易（港股业主）
- OpenAlex/Crossref（学术核验）
