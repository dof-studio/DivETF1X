# DivETF1X

DivETF1X Strategy - Automatically updated official factor release. You can see the daily automatic updates of the strategy here.

# Access to Our Data

Please access [DivETF1X Homepage](https://dof-studio.github.io/DivETF1X/) to view our latest release.</br>
请访问[DivETF1X 主页](https://dof-studio.github.io/DivETF1X/)以获取我们的最新更新。</br>

**什么是DivETF1X**

* **DivETF1X**指标是DOF Studio旗下DOF Think Tank所领导的Project Theia金融计划的新兴核心产物之一。Project Theia是一个公开性计划，旨在为最广泛人群提供公开免费的投资策略与投资科普，以实现投资人类共同未来、积累人类共同财富的目的。Project Theia所公开的成果包含一系列金融指标，由于金融指标普遍具有时限性，DivETF1X指标将用版本号区分指标的更新。例如，截至目前，本文中使用的指标模型版本为DivETF1X01（构建日期：2026-08-31）。
* 不同于天生投资于境外资产的SPYDL1D，DivETF1X指标本质是基于中国`红利ETF华泰柏瑞(510880.SS)`开发的交易型宽基指数策略指标。DivETF1X01作为MML Core Development和DOF Think Tank团队开发的实验性逐日双频方向性交易策略之一，其选择了可投资性更强、且综合具有长期上涨趋势的A股红利型ETF，使用完全非机器学习的量化分析技术，主要目的在于作为稳健的投资压舱石，借助蓝筹分红型股票组合的长期上涨趋势、以及DOF Think Tank成熟的回撤控制技术在获取红利收益的同时严控投资的风险，期以达到更高的夏普比率和更稳定的净值变化体验，适合在完全合规情况下期望取得稳健收益的中国投资者。
* DivETF1X系列指标以及Project Theia全部计划均使用完全开源且免费的工具和公开技术，包括MML、BtA、FactorModels、Statisticality等，所有框架均为团队自主研发，所基于的平台均是开源平台。若想了解所使用的开源工具，欢迎阅读最后一部分，以及参考dof-studio在GitHub上的其他开源仓库。
* 请记住，投资于原生金融资产投资的是人类未来，它完全可以不是一个零和博弈。DOF Studio的所有成员愿以最诚挚的热情投身于人类美好事业的投资与发展中。
* **注意**：Project Theia所公开的成果包含一系列金融指标，由于金融指标普遍具有时限性，DivETF1X指标将用版本号区分指标的更新。例如，截至目前，本文中使用的指标模型版本为DivETF1X01（构建日期：2029-08-31）。

**更新**

DivETF1X现在由程序自动计算和自动更新，将每日盘内不定时和盘后计算指标值。</br>
您现在可以通过GitHub Pages的方式实时访问该指标。</br>
团队认为，在自动化的更新下，指标的更新延迟能够缩减到15分钟以内。

**交易频率**

区别于旧版SPYDL1D01，DivETF1X01在构建之初就天然使用了DOF Studio提出的*单日双频*交易理念，其中，对于诸如”2026-09-02A“的以A结尾的日期下的投资决策，为以开盘价格进行投资交易的决策，而对于诸如”2026-09-02C“的以C结尾的日期下的投资决策，为以收盘价格进行投资交易的决策。单日双频的交易决策能够在不显著提高交易频率的情况下给予投资者更加灵活的调仓空间，并且收到开收盘竞价流动性的影响，双频交易不会显著影响交易滑点以及带来的额外成本。

**免责声明**

注意，本人以及研究团队不对指标的更新频率、更新时间、以及指标表现做任何担保。本指标仅供研究和学习使用，不构成任何投资建议。任何投资均有风险。依据本指标所进行的任何投资操作所带来的任何风险和任何法律后果，以及任何潜在后果均由投资人自行承担。

**当前版本** 

当前版本：V1
