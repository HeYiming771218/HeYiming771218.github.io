---
layout: about
title: About
permalink: /
subtitle: 
profile:
  align: right
  image: my-photo.jpg
  image_circular: true # crops the image to make it circular
  address: 
news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

<style>
/* 仅桌面端显示 */
@media (min-width: 768px){
  .about-wrap{ position:relative; }          /* 让花纹相对整段正文定位 */
  .decor-left,
  .decor-right{
    position:absolute;
    top:50%;                                  /* 垂直居中 */
    transform:translateY(-50%);
    width:260px;                              /* 想再大/再小自己调 */
    opacity:0.15;                             /* 淡一点，当背景 */
    z-index:0;
    pointer-events:none;                      /* 不影响鼠标选中文本 */
  }
  .decor-left { left:-380px; }                /* 负值→伸到正文区域外 */
  .decor-right{ right:-380px; }
}
/* 手机端直接隐藏 */
@media (max-width: 767px){
  .decor-left,.decor-right{ display:none; }
}
</style>

<!-- 花纹本身 -->
<div class="about-wrap">
  <img src="/assets/img/left.png"  class="decor-left"  alt="">
  <img src="/assets/img/right.png" class="decor-right" alt="">

<p style="font-size: 4.8em; font-weight: bold; color: #333;">
 何逸铭
</p>
我是南京大学新闻传播学院新闻与传播专业（2025~2028）的一年级硕士生，师从尚可可，目前在计算传播中心实验室工作。我的研究兴趣主要为<strong>计算传播、数据新闻</strong>。

<div class="about-purple-box">
_  ✍🏼 在方法论方面，我擅长通过大规模数字足迹数据挖掘、分析新闻生产以及其他人类行为。我精通 Python，并精通 R 语言，尤其擅长统计建模、自然语言处理和因果推断等应用。
</div>
<br>
___

<div class="about-purple-box">
_  💡 作为一名计算传播学研究人员，我致力于突破计算方法的界限，开发新的框架来分析新闻生产中的复杂元素（例如身份、语境、叙事和修辞），并追踪这些元素如何揭示新闻受众心理和行为的演变动态。
</div>
<br>
___
<div class="about-purple-box">
🤩 我的作品发表在《新闻与传播研究》、《国际新闻界》、《现代传播》、《新闻大学》以及《New Media & Society》等顶级期刊上。我的研究得到了四项内部和外部资助，并获得了美国国家传播协会（NCA）颁发的两项学术荣誉：政治传播分部最佳论文奖和人类传播与技术分部最佳学生论文奖。
</div>
<br>


<img src="/assets/img/my-photo3.jpg" align="middle" width="800px">


<br>

<a href="https://github.com/SocratesClub/SocratesClub.github.io/edit/master/_pages/about.md">
  <img src="https://user-images.githubusercontent.com/543384/192227995-fdb3a693-2f68-4dc4-b9bd-06053066322f.png" width = "800" align="middle" />
</a>

<br>

<style>
.about-purple-box {
  display: inline-block;          
  border: 1px solid;
  border-image: linear-gradient(135deg, #9b59b6 0%, #6a3093 100%) 1;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(154, 89, 182, 0.25);
  padding: 0.5rem;                
  margin: 0 auto;                
}
</style>
</div>
