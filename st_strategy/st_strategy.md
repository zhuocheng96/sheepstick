Workflow - Draft
---
1. report fetching automation
TODO keyword list
TODO data source
TODO data size

data source
- 全国破产信息网 https://pccz.court.gov.cn/pcajxxw/index/xxwsy
- 巨潮资讯 https://www.cninfo.com.cn/new/index.jsp

2. report analysis
TODO key information
TODO fixed formatted report
TODO result to structured data

3. trading strategy exploration
Manual process at the moment
TODO take notes so that we can automate this process in the future

4. trading strategy generation & backtesting
Half manual & Half LLM

5. full automation 
TODO connect to real trading platform
TODO connect to risk management platform
TODO connect to ORM

Idea
---
phase 1 - 预重整 (likely) 被申请重整/法院受理预重整 -> 公告签订预重整投资协议
phase 2 - 法院正式受理破产重整（路条, 9月/10月高峰期，研究从8月底开始 -> 签订正式投资协议

Back Testing Workflow updated - 20250727 - 01
---
1. stock scanner
construct stock pool

2. fetch reports
determine the start time and stop time of phase 1 and phase 2

3. construct back test dataset
fetch stock price change of stocks in the pool during phase 1 and phase 2

4. statistical analysis