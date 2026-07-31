# 江西旅行计划 · jiangxi-trip

## 仓库
- **GitHub**: `tiantian-0525/jiangxi-trip`
- **GitHub Pages**: https://tiantian-0525.github.io/jiangxi-trip/
- **本地目录**: `C:\Users\19103\trip-workspace`

## 项目文件
- `index.html` — 交互式旅行计划页面（Leaflet 地图 + 每日时间轴）
- `trip-plan.md` — 完整文字版行程（Markdown）
- `CLAUDE.md` — 本文件

## 部署方式
- `main` 分支 → 代码开发
- `gh-pages` 分支 → 部署到 GitHub Pages（只含 index.html）
- 部署命令：`git push origin main && git push origin gh-pages`

## 行程概览
- **时间**: 8月2日（日）00:45 → 8月8日（六）11:30
- **路线**: 南昌 → 景德镇 → 婺源 → 三清山 → 葛仙村 → 上饶机场
- **人数**: 两人

## 各天主题
| Day | 日期 | 地点 | 主题 |
|-----|------|------|------|
| D1 | 8/2 日 | 南昌 | 滕王阁+万寿宫 |
| D2 | 8/3 一 | 南昌→景德镇 | 省博+陶溪川 |
| D3 | 8/4 二 | 景德镇 | 陶瓷博物馆+DIY+图味美小黄鱼+汉服妆造 |
| D4 | 8/5 三 | 景德镇→婺源 | 古窑+李坑+月亮湾+婺女洲 |
| D5 | 8/6 四 | 婺源 | 石门峡漂流+篁岭+古风妆造 |
| D6 | 8/7 五 | 三清山→葛仙村 | 三清山全景大圈+仙侠妆造+葛仙村夜景 |
| D7 | 8/8 六 | 葛仙村→上饶机场 | 返程 |

## 数据结构
`index.html` 中的 `DAYS` 数组包含所有行程数据。每个 day 有 `locations[]`，每个 location 的 type 可选：`food` / `spot` / `hotel` / `transport` / `drink` / `dress`

## 已有功能
- Leaflet 地图 + 每日标注 + 路线连线
- iOS 风格 Action Sheet 导航（Apple Maps/Google Maps/高德）
- 小红书/大众点评深度链接
- 支付提醒、预算、备选方案
- 妆造建议（dress 类型，粉色标记）
