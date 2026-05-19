<div align="center">

# 钱袋 · MoneyMap

**把你的钱装一起 · 本地优先**

[![iOS](https://img.shields.io/badge/iOS-17.0%2B-black?style=flat-square&logo=apple)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.0-orange?style=flat-square&logo=swift)](https://swift.org)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-5-blue?style=flat-square)](https://developer.apple.com/xcode/swiftui/)
[![Privacy](https://img.shields.io/badge/Privacy-Local%20First-green?style=flat-square)](https://sakurallxa.github.io/moneymap-site/privacy.html)

</div>

---

## 一句话

钱袋是一款本地优先的个人资产记账 App。把现金、基金、A 股、港股、美股、黄金、定投装在同一个口袋里,一眼看到全部资产 + 今日盈亏,不需要打开 N 个 App。

## 设计理念

- **多渠道汇总** — 现金、基金 App、券商(A/港/美)、黄金、DCA 一站记录
- **本地优先** — 数据存设备本地,可选 iCloud 加密同步,**无后端、无账号、无追踪**
- **一眼可见** — 主屏 Widget + Hero 卡 + 趋势图 + 资产分布,信息密度极高
- **不打扰** — 不推送、不推荐、不分析、不广告

## 核心功能

| 模块 | 说明 |
|---|---|
| 多账户 | 现金 / 货币基金 / 基金 App / A 股 / 港股 / 美股 / 黄金 |
| 多币种 | CNY / HKD / USD,自动按汇率换算总值 |
| 行情自动 | 天天 / 蛋卷 / 新浪 / 雅虎 / 上海黄金交易所 |
| 定投计划 | 每天 / 每周 / 每两周 / 每月,T+1 自动确认,手续费率自动计算 |
| 再平衡 | 设置目标配置,系统计算偏离度,一键预填买卖建议 |
| 主屏 Widget | 小 / 中尺寸,黑金渐变 |
| Face ID 锁 | 启动 + 后台回来需验证 |
| iCloud 同步 | 可选,通过 Apple ID 加密 |
| 数据导出 | 一键 `.json` 完整备份 / `.csv` 持仓表格 |

## 技术栈

- **SwiftUI** + **SwiftData**(iOS 17+)
- **WidgetKit** Extension
- **CloudKit** Private Database(iCloud 同步)
- **LocalAuthentication**(Face ID)
- **思源宋体 SC**(品牌字体,运行时通过 CTFontManager 注册)

## 资产 / Brand

- 主色:**铜金 `#C8956D`** + **米色页面 `#F2EDE4`** + **黑金 Hero `#16140F → #2E2117`**
- 字体:思源宋体 SC(Regular / Medium / Light / ExtraLight)
- PnL:**红涨绿跌**(`#E63946` / `#1B7F47`),与 A 股惯例一致

## 隐私

钱袋不收集任何用户信息,不发送追踪数据,不接入广告 / 分析 SDK。

📋 [完整隐私政策 →](https://sakurallxa.github.io/moneymap-site/privacy.html)

## 联系

📮 [myrt.chaos@gmail.com](mailto:myrt.chaos@gmail.com)

---

<div align="center">

© 2026 钱袋 · MoneyMap

</div>
