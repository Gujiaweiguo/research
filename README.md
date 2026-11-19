# 商业地产研究档案（本地正典）

> 纪律：**所有产出先存本地，再推 IMA**。IMA 推送失败不影响本地存档；本目录是唯一正典，IMA 是分发渠道。

## 目录结构

| 路径 | 内容 | 更新频率 |
|---|---|---|
| report-v1.md | 主报告 v1.2：AI 商管/会员/数字员工产品研究（五道采纳门、字段引擎/解释引擎、§12 产品决策） | 手动迭代 |
| top100-ai-applications-v1.md | 赢商百强前 20 AI 应用盘点（分档、六条路径、证据等级） | 手动迭代 |
| winshang-top100-2025.md | 赢商 2025 百强榜完整名单（正典客户清单） | 年度 |
| m1-us-cn-head-clients-v1.md | 中美头部客户图谱 | 手动迭代 |
| m3-vendor-landscape.md | 中美供应商格局 | 手动迭代 |
| cre-research-plan.md | 研究计划 | 手动迭代 |
| competitors.md | 竞对清单（分类/抢哪块预算/AI实践/证据等级），随四维情报每周更新 | 每周五 |
| news/YYYY-MM-DD.md | 每日中美商地 AI 日报（cron cre-ai-news-daily，每天 06:00） | 每日 |
| 4dim/YYYY-WW.md | 四维情报周报（cron cre-ai-weekly，每周五 17:00：行业趋势/客户应用/竞对实践/机会建议） | 每周五 |
| weekly/ | （已废弃的旧周报路径，保留历史） | - |

## 四维框架（2026-11-19 Jason 定）

1️⃣ 行业趋势——企业用 AI 的应用
2️⃣ 客户应用——美国、中国商业地产客户
3️⃣ 竞对实践——竞对清单见 competitors.md，逐渐总结
4️⃣ 机会建议——给 Jason 的 AI 应用机会建议

## 证据分级（所有文档统一）

【官方披露】>【企业自述】>【媒体报道】>【待核】；事实只认一手来源；软文不当事实。

## 分发通道（2026-11-19 Jason 定：日报、周报、所有研究文档都推）

| 通道 | 位置 | 覆盖 |
|---|---|---|
| GitHub | Gujiaweiguo/research（main，本地经 `git subtree push --prefix=research research main`） | 全部文档 |
| IMA | 文件夹「商业地产」+ 知识库「商业地产」 | 全部文档 |

## IMA 分发

- 文件夹「商业地产」+ 知识库「商业地产」（动态查找：list_note_folder_by_cursor / search_knowledge_base）
- 凭证：/root/.config/ima/（见 ima-note-delivery 技能）
- 本目录 git 提交即版本保护
