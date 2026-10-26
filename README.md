# 你好，我是马璐雅 👋

量化研究 / 金融工程方向，目前正在求职（开放校招机会）。
我喜欢从公开数据里找规律，把市场里的"价差、错位、微观结构"变成可验证的研究结论。

---

## 🔬 研究兴趣

- **跨市场套利**：同一品种在不同市场之间的价格错位与回归
- **价差 / 基差研究**：内外盘价差、期现基差的结构与驱动因素
- **加密做市与微观结构**：订单簿、流动性、做市商行为（market microstructure）
- **多因子**：横截面选股与因子构建（multi-factor）

## 📌 精选项目

- **[AShare Forge：A 股截面因子研究平台](https://github.com/maluyantu-del/ashare-forge)**
  只用公开免费数据（baostock）搭建的本地因子研究流水线：T+1 可交易回测（涨跌停、停牌、退市清算、现金账户）、零假设校准、分层门槛、泄漏检测与带代码指纹的台账，153 项测试。十几个因子全部未过门槛，负结果照实记录，开发中踩过并修掉的偏差逐条列在 README 里。

- **[币安订单簿长跑记录器](https://github.com/maluyantu-del/binance-lob-recorder)**
  7×24 小时采集 BTC / ETH 前 10 档订单簿，靠更新编号首尾相接让数据"自证无漏"，每 10 分钟用独立快照逐档比对，27 项离线测试，附一小时真实样例数据。

- **[WTA 红土赛季价值投注模型](https://github.com/maluyantu-del/wta-clay-value-betting)**
  LightGBM 胜率模型 + 独立校准集的等渗校准 + 分数凯利回测，五项泄漏审计全部通过、结果可逐字节复现。2022–2024 测试集每注 +4.94%，但重抽样 95% 区间跨过 0，统计上不显著，README 如实写明。

- **[Avellaneda–Stoikov 做市报价模型](https://github.com/maluyantu-del/crypto-mm-avellaneda-stoikov)**
  接入 OKX 实时订单簿的入门实现，比较模型报价与市场价差、库存对储备价的影响；README 记录了参数量纲不一致的问题与离线复算结果。

- **[Jump Trading / Jump Crypto 深度机构研究报告](https://github.com/maluyantu-del/jump-trading-research)**
  一份完全基于公开信息的独立研究报告：拆解 Jump 的"研究—基础设施—执行—风控—资本"一体化业务模式、加密做市与微观结构布局，以及监管与诉讼带来的尾部风险。

- **[加密"永续 vs 现货"基差研究 + 资金费捕捉回测](https://github.com/maluyantu-del/crypto-basis-arb)**
  用公开免费数据（币安 / CCXT）从零搭建：测算 BTC 永续与现货的基差结构，对最朴素的"吃资金费"市场中性策略做**扣费回测**，得到一个诚实的负面结论（低费率环境下扣费即亏），附完整可复现代码与图表。

## 🛠️ 常用工具

`Python` · `pandas` · `NumPy` · `LightGBM` · `scikit-learn` · `SQLite` · `pytest` · 数据清洗与统计分析 · 金融时间序列

## 📫 联系我

- GitHub：[@maluyantu-del](https://github.com/maluyantu-del)
- 邮箱（GitHub 私密转发地址）：275576051+maluyantu-del@users.noreply.github.com

---

> 我的研究均基于公开信息整理与交叉验证，仅供学习交流，不构成任何投资建议。
