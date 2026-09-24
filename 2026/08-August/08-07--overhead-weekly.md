# overhead · 0803–0807

日期: 2026年8月7日
標籤: weekly

这周主线是「收尾验收 + 核算绩效」——把之前做的提效工具挨个发邮件验收，为优化奖励绩效铺路；壳牌和集团案件管理系统各推进了一小步，但大半时间被商道积分导数据、整理 Excel 这类事务占满，体感是重复性事务偏多的一周。

## 🧩 主线

### 提效工具验收 + 绩效核算

- 周一起把做过的提效工具挨个发邮件验收，为「优化奖励绩效」做准备。
- 周二、周三持续统计优化工作明细、发邮件收尾。

### 壳牌 shell_convert / SDCC 上传

- 周三改好几个转换逻辑（4 行代码 ✅）。
- 剩下的核心待办：**转后模板用 RPA 定时导入 SDCC 系统**——周四继续跟 AI 讨论重构方案。

### 集团案件管理系统

- 周二参加 IT 培训（通用模版：高新物流苏州）。
- 周四登陆并尝试配置，进度到 **3.1 新建模版**。

### 商道积分 / 招商随行

- 计划做一个招商随行自动化工具：做任务攒积分 + 自动导出后台数据。
- 周三、周五实际导出后台数据、整理 Excel（好累，又是 bullshit job）。

## 🧠 学到 / 想明白的

- **沙盒**：一个跑在远端的一次性 Linux 容器，LLM 通过终端 / 读写文件的方式操作它；打算顺着学 GitHub issues + Docker。
- **贫血模型 vs 富模型**：没有绝对对错——小项目、简单数据处理时「贫血」更简洁；业务复杂、状态多变时「富」更利于维护。
- **uv 好用**。
- 读了几篇：Open Weights and American AI Leadership、How Do We Stop Vibe Coding、重读 Pragmatic Engineer《When AI writes almost all code》。

## 💡 杂七杂八

- **本周体感是「事务性收尾期」**：发邮件、导数据、整理 Excel 占了大头，bullshit job 感强，专门收藏了 David Graeber《论狗屁工作现象》全文共鸣。
- 两句记在心里的话：Goodhart's law——「当一个指标变成目标，它就不再是个好指标」；尼采——「Hat man sein *Warum?* des Lebens, so verträgt man sich fast mit jedem *Wie?*」。
- 项目状态盘一下：壳牌 shell_convert 逻辑已改完 ✅，RPA 定时导入 SDCC 待落地；案件管理系统配置到 3.1。下周口子：壳牌 RPA 导入 SDCC 落地 + 案件管理系统继续配置 + 招商随行自动化工具动工。