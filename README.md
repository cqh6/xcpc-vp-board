# ICPC/CCPC VP 榜单系统

纯静态的 ICPC/CCPC 虚拟参赛（Virtual Participation）实时榜单系统。无需服务器、无需构建，直接在浏览器中打开即可使用。

代码由 AI 生成，可能有些小 bug

## 使用方式

直接打开 `index.html` 后进行选择即可

## 功能

- 实时 VP 计时与封榜（冻结期隐藏提交结果）
- 比赛结束后的回顾模式（时间轴滑块控制进度）
- ICPC 罚时计算与排名
- 奖牌分配（金/银/铜，按正式队排名确定）
- 学校排名
- 仅显示正式队伍过滤
- 题目提交详情弹窗

## 数据来源

比赛数据来自 [algoux/srk-collection](https://github.com/algoux/srk-collection)，通过 jsDelivr CDN 加载。

## 技术栈

- Vue 3
- js-yaml
- HTML / CSS / JavaScript
