---
title: "王春盛"
description: ""
---

<link rel="stylesheet" href="/css/aurora.css">

<div class="aurora-container" style="width: 100%; margin: 0 auto;">
  <div class="aurora-content">
    <div class="intro-text" style="margin-top: 0.6rem; max-width: 900px;">
      <p>你好！这里是我的博客。</p>
      <p>我关心技术、个人成长和内容创作。</p>
      <p>如果你好奇我<a href="{{< ref "now" >}}" class="aurora-link">正在做的事情</a>，或了解更多<a href="{{< ref "about" >}}" class="aurora-link">关于我</a>的信息。</p>
    </div>
  </div>
</div>


<script src="/js/Aurora.js" defer></script>
<script>
  // 确保页面完全加载后初始化Aurora效果
  document.addEventListener('DOMContentLoaded', function() {
    // 给浏览器一些时间来渲染DOM
    setTimeout(function() {
      const container = document.querySelector('.aurora-container');
      if (container) {
        // 确保容器尺寸适当
        function updateContainerSize() {
          // 设置为更宽更矮的尺寸
          const targetHeight = Math.min(window.innerHeight * 0.4, 300);
          container.style.height = targetHeight + 'px';
          container.style.width = '100%';
        }
        
        // 初始设置和窗口大小变化时更新
        updateContainerSize();
        window.addEventListener('resize', updateContainerSize);
      }
    }, 300);
  });
</script>
