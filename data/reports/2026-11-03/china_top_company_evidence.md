---
layout: page
title: "A股筛选与核验：证据台账（2026-11-03）"
permalink: /data/reports/2026-11-03/china-top-company-evidence/
---
[← A股AI产业分析：综合评分排名](/2026/11/03/a-share-ai-pick)

**声明：** AI生成内容，仅供参考，不构成投资建议。市场有风险，入市需谨慎。

<div style="overflow-x:auto" markdown="1">

# A股筛选与核验

| ID | Claim type | Claim/metric | Value and unit | Period | Release time | Retrieved at UTC | Source | Tier | Verification | Excerpt | Says |
|---|---|---|---|---|---|---|---|---|---|---|---|
| CTC-E01 | fact | 行情数据状态 | 5563只证券、2026-11-03 最终数据 | 2026-11-03 | 2026-11-03 | 2026-11-03T09:07Z | 行情数据库（状态） | P2-transparent-secondary | verified | latest_quote_days date 2026-11-03 最终数据 1 n 5563 | 行情数据有当日完整A股报价，可用于本次市场数据。 |
| CTC-E02 | fact | AI相关行业前100市值样本池 | 前100名，报价日2026-11-03 | 2026-11-03 | 2026-11-03 | 2026-11-03T09:08Z | 行情数据库（样本） | P2-transparent-secondary | verified | quote_date 2026-11-03 最终数据 true rows | 以申万二级行业关键词过滤后取市值前100，作为候选池。 |
| CTC-E03 | calculation | 初筛 | vintage 2026-09-30；scored=100 | 2026-09-30 | 2026-11-03 | 2026-11-03T09:08Z | 行情数据库（初筛） | P2-transparent-secondary | verified | weights quality 0.4 growth 0.25 valuation 0.2 liquidity 0.15 | 筛选按固定权重给出20名shortlist及敏感性。 |
| CTC-E04 | fact | 兆易创新三季报财务 | 营收202.97亿元；归母净利110.66亿元 | 2026年前三季度 | 2026-10-29 | 2026-11-03T09:19Z | http://dataclouds.cninfo.com.cn/shgonggao/hsomarket/2026/20261029/e15551946cda45b7b6e1b3f6bb237047.PDF | P1-primary | verified | 营业收入 8,731,610,944.35 ... 20,297,371,376.50 ... 197.11 | 兆易创新2026年前三季度收入与初筛值一致，增长来自存储芯片量价齐升。 |
| CTC-E05 | fact | 兆易创新驱动 | 存储芯片供给紧张、存储业务向好 | 2026年前三季度 | 2026-10-29 | 2026-11-03T09:19Z | 同上 | P1-primary | verified | 报告期内，存储芯片行业供给紧张，公司存储芯片产品量价齐升，存储业务持续向好 | 兆易创新的结果驱动来自存储芯片景气和MCU等产品线出货。 |
| CTC-E06 | fact | 兆易创新AI暴露 | 定制化存储方案服务推理需求 | 2026H1 | 2026-08-19 | 2026-11-03T09:20Z | http://static.cninfo.com.cn/finalpage/2026-08-19/1225480384.PDF | P1-primary | verified | AI 的发展对存储解决方案提出新的要求，公司控股子公司青耘科技...为客户提供契合其推理需求的解决方案 | 兆易创新AI层为硬件/存储，来自公司披露而非概念标签。 |
| CTC-E07 | fact | 长鑫科技三季报财务 | 营收2690.24亿元；归母净利1320.40亿元 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:19Z | https://static.sse.com.cn/disclosure/listedinfo/announcement/c/new/2026-10-31/688825_20261031_VWJ7.pdf | P1-primary | verified | 营业收入 118,714,029,752.18 ... 269,024,106,510.18 738.51 | 长鑫科技收入、净利与初筛值一致，存储周期驱动极强。 |
| CTC-E08 | fact | 长鑫科技AI暴露 | 端侧AI与长协 | 2026-10-30 | 2026-10-31 | 2026-11-03T09:18Z | http://dataclouds.cninfo.com.cn/shgonggao/investor/2026/20261031/28d024d8253df5d5c750e701ae616b97.pdf | P1-primary | verified | 随着 AI 向端侧加速渗透，LPDDR5X、LPDDR6 等低功耗高带宽产品需求急剧增长 | 长鑫科技披露端侧AI带动低功耗高带宽DRAM需求。 |
| CTC-E09 | fact | 长鑫科技减值反证 | 计提减值9.21亿元 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:20Z | http://dataclouds.cninfo.com.cn/shgonggao/hsomarket/2026/20261030/75675ab7acdd4897bd3bfd5b18975649.PDF | P1-primary | verified | 本期计提及确认的减值损失总额为920,820,520.75元 | 长鑫科技存在资产/存货减值反证，风险分较低。 |
| CTC-E10 | fact | 江波龙三季报财务 | 营收387.18亿元；归母净利143.22亿元 | 2026年前三季度 | 2026-10-30 | 2026-11-03T09:19Z | https://static.cninfo.com.cn/finalpage/2026-10-30/1225644948.PDF | P1-primary | verified | 营业收入（元）...38,718,231,824.00 131.37% | 江波龙收入和净利与初筛值一致。 |
| CTC-E11 | fact | 江波龙AI暴露 | 端侧AI合作拓展至AMD/高通/紫光展锐 | 2026Q3 | 2026-10-30 | 2026-11-03T09:19Z | 同上 | P1-primary | verified | 公司持续深化端侧 AI技术布局，相关技术合作范围进一步拓展至AMD、高通、紫光展锐 | 江波龙AI层为硬件/存储，披露了端侧AI和高端产品商业应用。 |
| CTC-E12 | fact | 中际旭创三季报财务 | 营收695.47亿元；归母净利222.38亿元 | 2026年前三季度 | 2026-10-30 | 2026-11-03T09:19Z | https://static.cninfo.com.cn/finalpage/2026-10-30/1225643953.PDF | P1-primary | verified | 营业收入 69,547,057,722.09 25,004,800,851.32 178.13% | 中际旭创收入与初筛值一致。 |
| CTC-E13 | fact | 中际旭创AI暴露 | 800G/1.6T光模块需求强 | 2026年前三季度 | 2026-10-30 | 2026-11-03T09:19Z | 同上 | P1-primary | verified | 高速光模块市场需求保持强劲，800G和1.6T 等高端光模块销售持续增加 | 中际旭创AI层为硬件/光模块，增长由AI算力基础设施带动。 |
| CTC-E14 | fact | 新易盛三季报财务 | 营收318.50亿元；归母净利113.72亿元 | 2026年前三季度 | 2026-10-29 | 2026-11-03T09:19Z | http://money.finance.sina.com.cn/corp/view/vCB_AllBulletinDetail.php?id=12679020&stockid=300502 | P2-transparent-secondary | verified | 营业总收入 31,849,895,741.23 ... 92.97% | 新易盛收入、净利与初筛值一致。 |
| CTC-E15 | fact | 新易盛AI暴露 | 人工智能算力投资带动收入 | 2026年前三季度 | 2026-10-29 | 2026-11-03T09:19Z | 同上 | P2-transparent-secondary | verified | 营业总收入...主要系报告期内公司受益于人工智能算力投资的发展 | 新易盛AI层为硬件/光模块，披露收入受AI算力投资带动。 |
| CTC-E16 | fact | 江波龙反证 | 经营现金流为-22.74亿元、存货增长 | 2026年前三季度 | 2026-10-30 | 2026-11-03T09:19Z | https://static.cninfo.com.cn/finalpage/2026-10-30/1225644948.PDF | P1-primary | verified | 经营活动产生的现金流量净额（元）...-2,274,022,802.87 | 江波龙扩张期现金流和存货是主要风险。 |
| CTC-E17 | fact | 中际旭创反证 | 存货238.78亿元、预付款锁料 | 2026-09-30 | 2026-10-30 | 2026-11-03T09:22Z | https://finance.sina.com.cn/roll/2026-10-30/doc-iniwxzqe2421061.shtml | P2-transparent-secondary | verified | 存货 238.78亿元...预付款 15.67亿元...提前向供应商长期锁定上游原材料 | 中际旭创强订单同时伴随存货/锁料和现金占用风险。 |
| CTC-E18 | fact | 源杰科技三季报财务 | 营收16.09亿元；归母净利10.24亿元 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:30Z | http://dataclouds.cninfo.com.cn/shgonggao/hsomarket/2026/20261030/9f0688552dee407d977350cdc4c0533d.PDF | P1-primary | verified | 营业收入 683,856,788.03 283.55 1,609,007,250.59 319.83 | 源杰科技财务值与初筛一致，收入增长来自数据中心业务。 |
| CTC-E19 | fact | 源杰科技AI暴露 | 数据中心业务收入大幅增长 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:30Z | 同上 | P1-primary | verified | 报告期公司收入增长，主要系数据中心业务收入大幅增长所致 | 源杰科技AI层为硬件/光芯片，受数据中心光互联需求带动。 |
| CTC-E20 | fact | 联讯仪器三季报财务 | 营收40.43亿元；归母净利20.06亿元 | 2026年前三季度 | 2026-10-30 | 2026-11-03T09:35Z | https://finance.sina.com.cn/wm/2026-10-29/doc-iniwxekr8734417.shtml | P2-transparent-secondary | verified | 前三季度，公司实现营业收入40.43亿元，同比增长401.91%；归母净利润20.06亿元 | 联讯仪器财务值与初筛一致。 |
| CTC-E21 | fact | 联讯仪器AI暴露 | 高速互联测试设备受AI算力拉动 | 2026Q3 | 2026-10-29 | 2026-11-03T09:35Z | 同上 | P2-transparent-secondary | verified | 受益于人工智能技术发展、全球算力需求提升以及数据中心建设进程加速，高速互联产品需求持续高速增长 | 联讯仪器AI层为硬件测试设备，服务光模块/光芯片扩产。 |
| CTC-E22 | fact | 三环集团三季报财务 | 营收115.03亿元；归母净利38.65亿元 | 2026年前三季度 | 2026-10-28 | 2026-11-03T09:35Z | https://www.nbd.com.cn/articles/2026-10-28/4623994.html | P2-transparent-secondary | verified | 前三季度上市公司实现营业收入115.03亿元，同比增长76.74%，归母净利润为38.65亿元 | 三环集团财务值与初筛一致。 |
| CTC-E23 | fact | 三环集团AI暴露 | 数据中心带动光器件；MLCC/陶瓷材料 | 2026H1/Q3 | 2026-10-28 | 2026-11-03T09:35Z | 同上 | P2-transparent-secondary | verified | 全球数据中心建设加快带动光器件需求，插芯及套筒等光通信产品销售同比增长 | 三环集团AI层为硬件/元件材料，受数据中心和光通信需求带动。 |
| CTC-E24 | fact | 长飞光纤三季报财务 | 营收191.24亿元；归母净利61.28亿元 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:30Z | https://stockmc.xueqiu.com/202610/601869_20261031_SL60.pdf | P1/P2 | verified | 一、营业总收入 19,124,479,317 ... 归属于上市公司股东的净利润 6,127,576,238 | 长飞光纤财务值与初筛一致。 |
| CTC-E25 | fact | 长飞光纤AI暴露 | 智算中心加速建设影响 | 2026年前三季度 | 2026-10-31 | 2026-11-03T09:30Z | 同上 | P1/P2 | verified | 主要源于受智算中心加速建设影响，行业进入上行周期 | 长飞光纤AI层为硬件/光通信，受智算中心建设带动。 |
| CTC-E26 | fact | 世纪华通三季报财务 | 营收332.98亿元；归母净利63.35亿元 | 2026年前三季度 | 2026-10-29 | 2026-11-03T09:35Z | https://m.jrj.com.cn/madapter/finance/2026/10/29094958921184.shtml | P2-transparent-secondary | verified | 前三季度，公司实现营业收入332.98亿元，同比增长22.31%；归母净利润63.35亿元 | 世纪华通财务值与初筛一致。 |
| CTC-E27 | fact | 世纪华通AI暴露 | AI工具与AI原生游戏 | 2026Q3/H1 | 2026-10-29 | 2026-11-03T09:35Z | 同上 | P2-transparent-secondary | verified | 人工智能领域，公司各业务板块加快推进AI工具与核心业务流程整合...探索AI原生游戏方向 | 世纪华通AI层为应用/游戏和AI云数据。 |
| CTC-E28 | fact | A股交易约束 | T+1、涨跌幅限制、科创/创业板20% | 2026-11-03 | 2026-11-03 | 2026-11-03T09:23Z | 交易所通行规则（本次未打开独立页面） | C-context-only | candidate | A股实行T+1与价格涨跌幅限制 | A股可得性约束需提示，但本行未作为排名输入。 |

</div>
