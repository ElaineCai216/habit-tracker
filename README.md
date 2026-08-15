# 习惯打卡 · Habit Tracker

一个自包含的单文件习惯打卡网页（Quartz 风格），无需安装、无需联网、双击 `index.html` 即可使用。

## 功能

- 添加 / 重命名 / 删除习惯（可配 emoji 图标）
- 每日勾选打卡，完成项自动变灰 + 删除线
- 今日完成进度（圆环 + 进度条）
- 近 7 天历史，可查看并补卡
- 连续打卡天数
- 数据保存在浏览器 `localStorage`（键 `habit-tracker:v1`），按日期归档

## 使用

直接双击 `index.html` 打开即可。数据只保存在当前浏览器中。

## 技术

原生 HTML + CSS + JavaScript，零依赖，无外部资源，离线可用。
视觉灵感来自 Bernardo Henning《Quartz》的编辑插画风格。
