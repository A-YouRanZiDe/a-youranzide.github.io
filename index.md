---
layout: article
title: 主页
---

-----

<span style="font-size: small;">一只悠然自得的个人主页</span>

欢迎来到我的个人主页！

你可以 [点这](https://space.bilibili.com/3493140812008017) 进入我的B站个人主页！

这是我的唯一官方网站！

<p>感谢我仅有的 </p> <span id="get_fans"></span> <p> 个粉丝</p>

有什么想法可以B站私信我或者邮箱发给我哦，邮箱在网站最下方的按钮那里！

<script> 
  fetch('https://space.bilibili.com/3493140812008017/') .then(response => { if (!response.ok) { throw new Error('Network response was not ok'); } return response.text(); }) .then(data => { const parser = new DOMParser(); const htmlDoc = parser.parseFromString(data, 'text/html'); const pContent = htmlDoc.querySelector('#n-fs .n-data-v.space-fans p').textContent; document.getElementById('get_fans').textContent = pContent; }) .catch(error => console.error(error)); 
</script>


[主页](a-youranzide.github.io/) 
[关于](a-youranzide.github.io/qbout.html) 


