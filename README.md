# mlb-baseball-replay

定时生成并发布 MLB 比赛回放页面到 GitHub Pages。


## Rendered Page Features

页面核心是单场比赛的 play-by-play 回放，主要包含：

- 按半局分段展示（Top/Bottom + 局数）
- 每个打席的结果徽章与事件描述
- 盗垒、换投、代打、代跑、runner out 等过程事件
- 打席前状态信息（垒包占用、出局数、当前比分）
- 关键节点后的状态条（base/out/score chip）
- 打者与投手面板：
  - 头像、姓名、守位/投手左右手信息
  - 打席前累计数据（如 AB/H、P/IP、ER/H/K/BB）
  - 打者近期事件标签
- 点击球员头像可跳转到 Baseball Savant 球员详情页
