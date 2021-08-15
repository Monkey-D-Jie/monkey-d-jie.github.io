---
layout:     post                    # 使用的布局（不需要改）
title:      IDEA使用GitHub报错问题排查与解决           # 标题 
subtitle:   IDEA中把GitHub用起来，真香！　#副标题
date:       2021-08-15           # 时间
author:     BY jie                    # 作者
header-img: img/post-bg-BJJ.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - 工作
    - IDEA
---
## 工欲善其事必先利其器

　　在日常的开发中，如果有遇到那些神奇的，让人拍手叫绝的代码，实在让人难忍收藏的冲动。最好的收藏莫过于将它们放在云端，而GitHub就是这样一快宝地了。
　　
　　笔者遇到的情况是IDEA中的GitHub账户是ok的，但在上提代码的时候，却报了“Perimssion denied”的错误。由于之前从没有遇到过，所以毫不犹豫地就选择了去网上查找资料。在搜罗了一番后，终于到了一剂良药。
　　
　　良药出处：[Git使用出现git@github.com: Permission denied (publickey)](https://blog.csdn.net/qq_43768946/article/details/90411154)
　　
　　简单来说就是，当在IDEA中使用GitHub时遇到了Permission denied的错误。大概率是你的GitHub的公钥过期了，所以需要重新在自己的GitHub上注册一个。
　　
  
　







