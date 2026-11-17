# DianLeida 店雷达 1688电商选品 Skill / MCP
> 仓库标识：dsh-dianleida-ecommerce-product-selection
> 版本：v1.1.0
> 类型：MCP + Skill 混合插件
> 适配：DSH 平台

## 简介
店雷达 DianLeida 选品MCP，集成5大核心选品能力：选品库、产品排名查询、产品数据分析、类目筛选、同款识图检索。
接入后可直接调取1688平台真实商品数据，自动输出选品分析结论，无需手动复制搬运数据，适合跨境电商、1688货源选品、Temu/TikTok Shop/Shopee 卖家。

## 能力列表
- product_selection_library：选品库查询，按类目、热度筛选货源
- product_ranking：商品排名查询，查看类目爆款榜单
- product_analysis：商品数据分析，利润、销量、价格、供应商评估
- category_filter：类目筛选，快速定位细分货源赛道
- image_search_similar：图片搜同款，以图找1688同源货源

## 所需配置项
| 配置Key | 说明 | 是否必填 |
| ---- | ---- | ---- |
| dianleida_api_key | 店雷达API密钥 | ✅ 必填 |
| platform | 目标平台，可选：1688 / temu / tiktok / amazon / shopee | ❌ 选填，默认1688 |

## 安装方式
1. 在DSH插件市场搜索 `dsh-DianLeida-E-commerce-product-selection`
2. 下载 Release 中的 zip 包，在DSH内导入Skill包
3. 填入你的 `dianleida_api_key`，保存配置即可使用

## 标签
dsh-plugin, mcp, skills, ecommerce, cross-border-ecommerce, product-selection, 1688, amazon, temu, tiktok, shopee, coze, workbuddy

## 版本日志
v1.1.0
- 初始发布，支持5项选品核心能力
- 适配DSH MCP调用规范

## 开源协议
MIT License
