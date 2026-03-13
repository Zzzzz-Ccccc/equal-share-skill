# 看究竟-数据服务接口文档索引

> **名称**: `看究竟-金融数据服务` · **版本**: `1.0-SNAPSHOT` · **文档文件**: `skill.md` · **条目数**: 57 · **生成时间**: 2026-03-13 00:08:00

编译期根据 @Skill 生成的接口索引；详细说明在 reference/ 下单个 md，按需加载以节省 token。

## 元数据

| 键 | 值 |
|----|-----|
| name | `看究竟-金融数据服务` |
| description | 编译期根据 @Skill 生成的接口索引；详细说明在 reference/ 下单个 md，按需加载以节省 token。 |
| version | `1.0-SNAPSHOT` |
| document | `skill.md` |
| title | 看究竟-数据服务接口文档索引 |
| type | `skill-index` |
| generated_at | `2026-03-13T00:08:00.3467019` |
| total_interfaces | 57 |
| reference_dir | `reference/` |
| companion_json | `skill-reference.json`（按名调用映射） |

---

equal看究竟推出的专业级金融数据服务解决方案，通过统一标准化API接口，为机构与个人投资者提供一站式数据服务。
核心数据覆盖：
行情数据：A股全市场、公募基金、主流指数的实时与历史行情
财务数据：全A股上市公司定期报告与财务指标（资产负债表、利润表、现金流量表等）
基金画像：基金经理多维画像数据，涵盖任职履历、管理规模、业绩归因、投资风格等深度信息
服务优势： 标准化接口设计、实时数据更新、企业级稳定性保障，助力用户高效获取高质量金融数据资产。

## 文档说明

- **总计**: 共 **57** 个接口文档
- **格式**: Markdown
- **位置**: `reference/`（可按 `group` 分子目录，每条接口一篇 md）
- **更新**: 编译期生成，与 `@Skill` 保持一致

---

## 究竟策略

**数量**: 13 个接口

| 序号 | 接口名称                                               | 文档ID                                         | 文档路径  |
|------|------------------------------------------------------|-----------------------------------------------|----------|
| 1 | 究竟策略列表页 | /api/tool/outcome/strategy/list | [究竟策略列表页.md](reference/小工具-究竟策略/究竟策略列表页.md) |
| 2 | 究竟策略首页 | /api/tool/outcome/strategy/home/page | [究竟策略首页.md](reference/小工具-究竟策略/究竟策略首页.md) |
| 3 | 究竟策略基本信息 | /api/tool/outcome/strategy/base | [究竟策略基本信息.md](reference/小工具-究竟策略/究竟策略基本信息.md) |
| 4 | 策略组合当前持仓日期列表 | /api/tool/outcome/strategy/holding/date | [策略组合当前持仓日期列表.md](reference/小工具-究竟策略/策略组合当前持仓日期列表.md) |
| 5 | 策略组合调仓明细日期列表 | /api/tool/outcome/strategy/trade/detial/date | [策略组合调仓明细日期列表.md](reference/小工具-究竟策略/策略组合调仓明细日期列表.md) |
| 6 | 策略组合当前持仓 | /api/tool/outcome/strategy/current/holding | [策略组合当前持仓.md](reference/小工具-究竟策略/策略组合当前持仓.md) |
| 7 | 策略组合持仓买卖明细 | /api/tool/outcome/strategy/deal/detial | [策略组合持仓买卖明细.md](reference/小工具-究竟策略/策略组合持仓买卖明细.md) |
| 8 | 究竟策略最新交易明细 | /api/tool/outcome/strategy/latest/trade | [究竟策略最新交易明细.md](reference/小工具-究竟策略/究竟策略最新交易明细.md) |
| 9 | 策略组合走势图数据 | /api/tool/outcome/strategy/trend/chart/data | [策略组合走势图数据.md](reference/小工具-究竟策略/策略组合走势图数据.md) |
| 10 | 策略组合-调仓信号 | /api/tool/outcome/strategy/change/signal | [策略组合-调仓信号.md](reference/小工具-究竟策略/策略组合-调仓信号.md) |
| 11 | 策略组合-资产分布 | /api/tool/outcome/strategy/asset/allocation | [策略组合-资产分布.md](reference/小工具-究竟策略/策略组合-资产分布.md) |
| 12 | 策略组合-指标列表 | /api/tool/outcome/strategy/index/list | [策略组合-指标列表.md](reference/小工具-究竟策略/策略组合-指标列表.md) |
| 13 | 策略组合-组合分析 | /api/tool/outcome/strategy/analysis | [策略组合-组合分析.md](reference/小工具-究竟策略/策略组合-组合分析.md) |

## 高管持股

**数量**: 9 个接口

| 序号 | 接口名称                                               | 文档ID                                         | 文档路径  |
|------|------------------------------------------------------|-----------------------------------------------|----------|
| 1 | 持股变动-增减持金额排行榜 | /api/tool/manager/holding/rank | [持股变动-增减持金额排行榜.md](reference/小工具-高管持股/持股变动-增减持金额排行榜.md) |
| 2 | 持股变动列表 | /api/tool/manager/holding/change/list | [持股变动列表.md](reference/小工具-高管持股/持股变动列表.md) |
| 3 | 增减持计划列表 | /api/tool/manager/holding/plan/list | [增减持计划列表.md](reference/小工具-高管持股/增减持计划列表.md) |
| 4 | 个股详情/动态详情--增减持操作明细数据 | /api/tool/manager/holding/{stockCode}/opt/detail | [个股详情/动态详情--增减持操作明细数据.md](reference/小工具-高管持股/个股详情_动态详情--增减持操作明细数据.md) |
| 5 | 个股增减持计划详情 | /api/tool/manager/holding/{stockCode}/plan/detail | [个股增减持计划详情.md](reference/小工具-高管持股/个股增减持计划详情.md) |
| 6 | 搜索（支持股票代码、股票名称、高管搜索） | /api/tool/manager/holding/search | [搜索（支持股票代码、股票名称、高管搜索）.md](reference/小工具-高管持股/搜索（支持股票代码、股票名称、高管搜索）.md) |
| 7 | 详情页基本信息（含数据分析） | /api/tool/manager/holding/{stockCode}/basic/info | [详情页基本信息（含数据分析）.md](reference/小工具-高管持股/详情页基本信息（含数据分析）.md) |
| 8 | 搜索详情接口 | /api/tool/manager/holding/{stockCode}/search/result | [搜索详情接口.md](reference/小工具-高管持股/搜索详情接口.md) |
| 9 | 高管持股变动日期列表 | /api/tool/manager/holding/date/list | [高管持股变动日期列表.md](reference/小工具-高管持股/高管持股变动日期列表.md) |

## 机构动向

**数量**: 18 个接口

| 序号 | 接口名称                                               | 文档ID                                         | 文档路径  |
|------|------------------------------------------------------|-----------------------------------------------|----------|
| 1 | 机构动向列表2.5.0 | /api/tool/agency/page/list/v250 | [机构动向列表2.5.0.md](reference/小工具-机构动向/机构动向列表2.5.0.md) |
| 2 | 机构风云榜榜单2.5.0-基础信息 | /api/tool/agency/basic/info/v250 | [机构风云榜榜单2.5.0-基础信息.md](reference/小工具-机构动向/机构风云榜榜单2.5.0-基础信息.md) |
| 3 | 机构风云榜-榜单详情数据2.5.0 | /api/tool/agency/rank/list/v250 | [机构风云榜-榜单详情数据2.5.0.md](reference/小工具-机构动向/机构风云榜-榜单详情数据2.5.0.md) |
| 4 | 机构风云榜-榜单首页2.5.0 | /api/tool/agency/rank/launch/v250 | [机构风云榜-榜单首页2.5.0.md](reference/小工具-机构动向/机构风云榜-榜单首页2.5.0.md) |
| 5 | 机构风云榜-产品列表 2.5.0 | /api/tool/agency/product/list/v250 | [机构风云榜-产品列表 2.5.0.md](reference/小工具-机构动向/机构风云榜-产品列表_2.5.0.md) |
| 6 | 机构风云榜-季度筛选列表 2.5.0 | /api/tool/agency/quarter/date/list/v250 | [机构风云榜-季度筛选列表 2.5.0.md](reference/小工具-机构动向/机构风云榜-季度筛选列表_2.5.0.md) |
| 7 | 首页机构动向 | /api/tool/agency/home/page | [首页机构动向.md](reference/小工具-机构动向/首页机构动向.md) |
| 8 | 机构持仓日期列表 | /api/tool/agency/holder/stock/date/list | [机构持仓日期列表.md](reference/小工具-机构动向/机构持仓日期列表.md) |
| 9 | 机构历史个股追踪 | /api/tool/agency/holding/track247 | [机构历史个股追踪.md](reference/小工具-机构动向/机构历史个股追踪.md) |
| 10 | 机构本期持股列表 | /api/tool/agency/current/list | [机构本期持股列表.md](reference/小工具-机构动向/机构本期持股列表.md) |
| 11 | 机构持仓列表 | /api/tool/agency/holder/stock/list | [机构持仓列表.md](reference/小工具-机构动向/机构持仓列表.md) |
| 12 | 机构详情 | /api/tool/agency/detail | [机构详情.md](reference/小工具-机构动向/机构详情.md) |
| 13 | 机构搜索 | /api/tool/agency/search | [机构搜索.md](reference/小工具-机构动向/机构搜索.md) |
| 14 | 机构动向-往期市值规模 | /api/tool/agency/capital/report | [机构动向-往期市值规模.md](reference/小工具-机构动向/机构动向-往期市值规模.md) |
| 15 | 机构动向-单个机构-往期市值规模 | /api/tool/agency/single/capital/report | [机构动向-单个机构-往期市值规模.md](reference/小工具-机构动向/机构动向-单个机构-往期市值规模.md) |
| 16 | 机构动向-下属分支机构列表(历史持股) | /api/tool/agency/branch/names | [机构动向-下属分支机构列表(历史持股).md](reference/小工具-机构动向/机构动向-下属分支机构列表(历史持股).md) |
| 17 | 机构动向-下属分支机构列表/股东列表(本期) | /api/tool/agency/current/branch/names | [机构动向-下属分支机构列表/股东列表(本期).md](reference/小工具-机构动向/机构动向-下属分支机构列表_股东列表(本期).md) |
| 18 | 机构动向-下属分支机构列表（全部） | /api/tool/agency/branch/agency/names | [机构动向-下属分支机构列表（全部）.md](reference/小工具-机构动向/机构动向-下属分支机构列表（全部）.md) |

## 龙虎榜

**数量**: 17 个接口

| 序号 | 接口名称                                               | 文档ID                                         | 文档路径  |
|------|------------------------------------------------------|-----------------------------------------------|----------|
| 1 | 首页-龙虎榜（前一个版本） | /api/tool/dragon/tiger/homepage | [首页-龙虎榜（前一个版本）.md](reference/小工具-龙虎榜/首页-龙虎榜（前一个版本）.md) |
| 2 | 首页-龙虎榜(最新版本) | /api/tool/dragon/tiger/homepage/new | [首页-龙虎榜(最新版本).md](reference/小工具-龙虎榜/首页-龙虎榜(最新版本).md) |
| 3 | 龙虎榜日期列表 | /api/tool/dragon/tiger/date/list | [龙虎榜日期列表.md](reference/小工具-龙虎榜/龙虎榜日期列表.md) |
| 4 | 游资榜列表 | /api/tool/dragon/tiger/hot/money/list | [游资榜列表.md](reference/小工具-龙虎榜/游资榜列表.md) |
| 5 | 营业部所属游资席位 | /api/tool/dragon/tiger/dept/belong/hot/money | [营业部所属游资席位.md](reference/小工具-龙虎榜/营业部所属游资席位.md) |
| 6 | 营业部操作明细 | /api/tool/dragon/tiger/dept/holding/detial/list | [营业部操作明细.md](reference/小工具-龙虎榜/营业部操作明细.md) |
| 7 | 游资详情(返回游资信息以及营业部信息) 2.4.9 | /api/tool/dragon/tiger/hot/money/dtl249 | [游资详情(返回游资信息以及营业部信息) 2.4.9.md](reference/小工具-龙虎榜/游资详情(返回游资信息以及营业部信息)_2.4.9.md) |
| 8 | 搜索 | /api/tool/dragon/tiger/search | [搜索.md](reference/小工具-龙虎榜/搜索.md) |
| 9 | 龙虎榜胜率排行榜2.4.9 | /api/tool/dragon/tiger/win_rate/rank | [龙虎榜胜率排行榜2.4.9.md](reference/小工具-龙虎榜/龙虎榜胜率排行榜2.4.9.md) |
| 10 | 龙虎榜单-个股榜2.4.9 | /api/tool/dragon/tiger/stock/{tradeDate}/rank | [龙虎榜单-个股榜2.4.9.md](reference/小工具-龙虎榜/龙虎榜单-个股榜2.4.9.md) |
| 11 | 龙虎榜单-游资榜2.4.9 | /api/tool/dragon/tiger/hot_money/{tradeDate}/rank | [龙虎榜单-游资榜2.4.9.md](reference/小工具-龙虎榜/龙虎榜单-游资榜2.4.9.md) |
| 12 | 龙虎榜单-营业部榜2.4.9 | /api/tool/dragon/tiger/dept/{tradeDate}/rank | [龙虎榜单-营业部榜2.4.9.md](reference/小工具-龙虎榜/龙虎榜单-营业部榜2.4.9.md) |
| 13 | 龙虎榜游资详情页-交易分析2.4.9 | /api/tool/dragon/tiger/detail/{hotMoney}/analysis | [龙虎榜游资详情页-交易分析2.4.9.md](reference/小工具-龙虎榜/龙虎榜游资详情页-交易分析2.4.9.md) |
| 14 | 龙虎榜日期列表（近1年/近1月）2.4.9 | /api/tool/dragon/tiger/recent/trade_date/list | [龙虎榜日期列表（近1年/近1月）2.4.9.md](reference/小工具-龙虎榜/龙虎榜日期列表（近1年_近1月）2.4.9.md) |
| 15 | 游资近期操作2.4.9 | /api/tool/dragon/tiger/hot/money/opt | [游资近期操作2.4.9.md](reference/小工具-龙虎榜/游资近期操作2.4.9.md) |
| 16 | 游资近1月操作日期列表2.4.9 | /api/tool/dragon/tiger/{hotMoney}/date/list | [游资近1月操作日期列表2.4.9.md](reference/小工具-龙虎榜/游资近1月操作日期列表2.4.9.md) |
| 17 | 市场高度 | /api/tool/dragon/tiger/market/high/{tradeDate}/rank | [市场高度.md](reference/小工具-龙虎榜/市场高度.md) |

---

## 分类统计

| 分类 | 接口数量 |
|------|---------|
| 究竟策略 | 13 |
| 高管持股 | 9 |
| 机构动向 | 18 |
| 龙虎榜 | 17 |
| **合计** | **57** |

> 生成时间: 2026-03-13 00:08:00
equal技能包及相关数据服务均为看究竟的知识产权。
未经书面许可，禁止复制、修改、传播本服务内容及数据。

免责声明：本服务提供的金融数据仅供参考，不构成投资建议。
数据使用需遵守相关法律法规及监管要求。
