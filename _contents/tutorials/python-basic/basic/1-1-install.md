---
description: 
chapter: 1
title: 网易云跟贴 评论测试
date: 2016-11-3
comments: false
---
* 学习资料:
  * [相关代码](https://gentie.163.com/)

<div id="cloud-tie-wrapper" class="cloud-tie-wrapper"></div>
<script src="https://img1.ws.126.net/f2e/tie/yun/sdk/loader.js"></script>
<script>
var cloudTieConfig = {
  url:  "{{site.url}}{{page.url}}", 
  sourceId: "{{page.url}}",
  productKey: "7ec85e7652dc4f3889d6e3d66b19953d",
  target: "cloud-tie-wrapper"
};
var yunManualLoad = true;
Tie.loader("aHR0cHM6Ly9hcGkuZ2VudGllLjE2My5jb20vcGMvbGl2ZXNjcmlwdC5odG1s", true);
</script>