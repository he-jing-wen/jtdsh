---
title: 首页
nav_order: 0
layout: single
---

<!-- 全局美化样式，只写在首页，不会触发scss编译失败 -->
<style>
/* 页面整体柔和背景 */
body {
  background-color: #f4f7ff !important;
}
/* 内容容器：圆角、阴影、加宽 */
.page__content {
  background: #ffffff;
  border-radius: 20px;
  padding: 40px;
  box-shadow: 0 4px 30px rgba(80, 120, 220, 0.08);
}
/* 顶部渐变横幅 */
.top-banner {
  background: linear-gradient(135deg, #6366f1, #8b5cf6);
  color: white;
  text-align: center;
  padding: 40px 20px;
  border-radius: 18px;
  margin-bottom: 30px;
}
.top-banner h1 {
  margin: 0;
  font-size: 32px;
  border: none !important;
  padding: 0 !important;
}
.top-banner p {
  opacity: 0.9;
  font-size: 17px;
  margin: 10px 0 0;
}
/* 分类卡片：悬浮上浮动画 */
.card-item {
  background: #f8faff;
  border-radius: 16px;
  padding: 26px;
  margin: 20px 0;
  transition: all 0.3s ease;
  border: 1px solid #eef2ff;
}
.card-item:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 30px rgba(99, 102, 241, 0.12);
}
/* 文档绿色跳转按钮 */
.doc-btn {
  display: inline-block;
  background: #10b981;
  color: white !important;
  text-decoration: none;
  padding: 7px 16px;
  border-radius: 10px;
  margin-left: 12px;
  transition: 0.2s;
}
.doc-btn:hover {
  background: #059669;
}
/* 游戏蓝色按钮组 */
.game-btn {
  display: inline-block;
  background: #6366f1;
  color: white !important;
  text-decoration: none;
  padding: 9px 18px;
  border-radius: 10px;
  margin: 8px 6px 0;
  transition: 0.2s;
}
.game-btn:hover {
  background: #4f46e5;
}
/* 标题美化 */
h2 {
  border-left: 6px solid #6366f1;
  padding-left: 14px;
  margin-top: 35px;
}
</style>

<!-- 顶部渐变横幅 -->
<div class="top-banner">
<h1>👋 我的学习生活小站</h1>
<p>学习笔记 · 影视书单 · 趣味小游戏</p>
</div>

<div class="card-item">
# 欢迎来到我的个人小站
这里存放我的全部学习资料、生活随笔、兴趣分享。
</div>

## 📂 站点分类
<div class="card-item">
1. 📚 课程学习笔记：各科知识点、错题整理、复习提纲
<a href="study.md" class="doc-btn">进入笔记库</a>
</div>

<div class="card-item">
2. 🎬 影视书单：观影读书心得与推荐清单
<a href="life.md" class="doc-btn">查看清单</a>
</div>

<div class="card-item">
3. 💡 生活碎碎念：日常记录、感悟与计划
<a href="life.md" class="doc-btn">生活记录</a>
</div>

<div class="card-item">
4. 🧩 趣味小应用：内嵌简易小游戏
<br>
<a href="click-speed.html" class="game-btn">点击测速小游戏</a>
<a href="guess-number.html" class="game-btn">猜数字小游戏</a>
<a href="game.md" class="game-btn">游戏总览页面</a>
<p style="margin:12px 0 0; color:#666;">后续会持续更新更多小游戏</p>
</div>
