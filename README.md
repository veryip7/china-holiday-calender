## 中国节假日补班日历

### 订阅地址
2019~2021年中国放假、调休和补班日历 更新时间2021-06-11 10:00:56
- 国内订阅地址(**支持定制补班日程**): [https://www.shuyz.com/githubfiles/china-holiday-calender/master/holidayCal.ics](https://www.shuyz.com/githubfiles/china-holiday-calender/master/holidayCal.ics)
- GitHub订阅地址(科学上网): [https://raw.githubusercontent.com/lanceliao/china-holiday-calender/master/holidayCal.ics](https://raw.githubusercontent.com/lanceliao/china-holiday-calender/master/holidayCal.ics)
- Telegram讨论组: [https://t.me/joinchat/EwhMZRVB7xI4OpuXLXukkw](https://t.me/joinchat/EwhMZRVB7xI4OpuXLXukkw)

### 特点
1. 节假日信息来自[中国政府网](http://www.gov.cn/)，一手信息、权威准确
2. 包含最近3年的节假日信息，机器人自动维护，更新及时
3. 日历标题包含放假、补班的天数信息
4. 日历标题包含放假、补班等关键字，方便脚本开发。例如使用`iPhone`的`快捷指令`应用编写工作日闹钟
5. 每个补班日程自动设置上班提醒，默认时间为`09:00~18:00`、提前一个小时提醒
6. 支持个性化定制补班日程的开始、结束时间和提醒时间

### 放假日程

日程表            |  详细信息
:-------------------------:|:-------------------------:
![](./holiday1.jpg)  |  ![](./holiday2.jpg)

### 补班日程

日程表            |  详细信息
:-------------------------:|:-------------------------:
![](./compensateday1.jpg)  |  ![](./compensateday2.jpg)

### 定制补班日程

支持指定补班日程的开始、结束时间和提醒时间，格式为：`订阅地址`?token=`API密钥`&compStart=`上班时分秒`&compEnd=`下班时分秒`&compAlarm=`提前多少分钟提醒`

例如补班时间为早上8.30到晚上8.30，提前15分钟提醒，则订阅地址为 `https://www.shuyz.com/githubfiles/china-holiday-calender/master/holidayCal.ics?token=cb429c2a-81a6-4c26-8f35-4f4bf0c84b2c&compStart=083000&compEnd=203000&compAlarm=15`

**注意:**
- 时间格式为24小时制的6位数字，个位补0，例如`8点零5分`表示为`080500`
- 定制功能需要额外消耗服务器的资源，若您的时间为朝九晚六请尽量避免使用此功能
- 由于订阅用户众多，如果定制用户影响到服务器的正常使用，则定制功能可能随时取消

定制补班日程表            |  详细信息
:-------------------------:|:-------------------------:
![](./customCompensateday1.png)  |  ![](./customCompensateday2.png)

### 快捷指令应用

节假日查询            |  节假日闹钟
:-------------------------:|:-------------------------:
![](./queryHoliday.jpg)  |  ![](./holidayAlarm.jpg)

### 捐助
`中国节假日补班日历` 属于个人业余项目，如果您愿意支持项目的开发，欢迎为其捐赠。

<div align="left">
	<img src="./wechatPay.jpg" alt="微信支付" width="35%">
</div>
