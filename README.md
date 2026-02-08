# Tushare OpenClaw Skill

[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://openclaw.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[English](#english) | [中文](#chinese)

---

<a name="english"></a>
## 🇬🇧 English

Tushare Pro financial data API skill for [OpenClaw](https://openclaw.ai) - Query Chinese stock market data including stocks, funds, futures, bonds, and macroeconomic indicators.

### Features

- 📈 **Stock Market Data** - Daily/weekly/monthly quotes, PE/PB ratios, market cap
- 💰 **Financial Statements** - Income, balance sheet, cash flow
- 📊 **Market Data** - Capital flow, limit-up/down stocks, top traders
- 🏢 **Company Fundamentals** - Basic info, IPO calendar
- 📅 **Trading Calendar** - Exchange holidays, trading days

### Installation

```bash
# Install via OpenClaw
openclaw skills install https://github.com/DayDreammy/tushare-openclaw-skill

# Or manually copy to your skills directory
cp -r tushare-api ~/.openclaw/skills/
```

### Structure

```
tushare-api/
├── SKILL.md              # Main skill definition
├── README.md             # This file
├── references/
│   └── api-reference.md  # Complete API documentation
└── scripts/
    ├── tushare_examples.py     # Usage examples
    └── analyze_bank_stocks.py  # Bank stock analysis demo
```

### Requirements

- Python 3.x
- `tushare` package: `pip install tushare`
- Tushare Pro Token (free registration at https://tushare.pro)

### Usage

Once installed, you can ask OpenClaw:

- "查询平安银行最近 30 天的股价" (Query Ping An Bank's stock price for the last 30 days)
- "获取贵州茅台的财务报表" (Get Kweichow Moutai's financial reports)
- "分析银行股的估值情况" (Analyze bank stock valuations)
- "查看今天的涨跌停股票" (Check today's limit-up/down stocks)

---

<a name="chinese"></a>
## 🇨🇳 中文

适用于 [OpenClaw](https://openclaw.ai) 的 Tushare Pro 金融数据 API Skill - 查询中国股票、基金、期货、债券和宏观经济数据。

### 功能特性

- 📈 **股票行情数据** - 日线/周线/月线、PE/PB 估值、市值
- 💰 **财务报表** - 利润表、资产负债表、现金流量表
- 📊 **市场数据** - 资金流向、涨跌停股票、龙虎榜
- 🏢 **公司基本面** - 基础信息、IPO 日历
- 📅 **交易日历** - 交易所节假日、交易日

### 安装

```bash
# 通过 OpenClaw 安装
openclaw skills install https://github.com/DayDreammy/tushare-openclaw-skill

# 或手动复制到 skills 目录
cp -r tushare-api ~/.openclaw/skills/
```

### 文件结构

```
tushare-api/
├── SKILL.md              # Skill 主定义文件
├── README.md             # 本文件
├── references/
│   └── api-reference.md  # 完整 API 文档
└── scripts/
    ├── tushare_examples.py     # 使用示例
    └── analyze_bank_stocks.py  # 银行股分析示例
```

### 依赖

- Python 3.x
- `tushare` 包: `pip install tushare`
- Tushare Pro Token（免费申请：https://tushare.pro）

### 使用方法

安装后，你可以问 OpenClaw：

- "查询平安银行最近 30 天的股价"
- "获取贵州茅台的财务报表"
- "分析银行股的估值情况"
- "查看今天的涨跌停股票"

---

## 🏗️ Community Submission

This skill has been submitted to the official OpenClaw skill directory:

本 Skill 已提交到 OpenClaw 官方技能仓库：

🔗 **PR**: https://github.com/openclaw/clawhub/pulls

---

## 📄 License

MIT License - See [LICENSE](LICENSE) for details.

## 👤 Author

- **GitHub**: [@DayDreammy](https://github.com/DayDreammy)
- **Skill Author**: yybot

## 🔗 Links

- [Tushare Pro](https://tushare.pro) - Official data platform / 官方数据平台
- [OpenClaw](https://openclaw.ai) - AI assistant platform / AI 助手平台
- [ClawHub](https://github.com/openclaw/clawhub) - Official skill registry / 官方技能仓库
