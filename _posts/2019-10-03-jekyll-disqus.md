---
layout: post
title: "지킬에 disqus 적용기"
date: 2019-10-04
excerpt: "지킬테마에 disqus 댓글 기능 적용하며 겪은 삽질 및 후기"
tags: [sample post, readability, image, feature]
feature: http://i.imgur.com/Ds6S7lJ.png
comments: true
---

지킬에 댓글 기능인 disqus를 적용하는데 좀 애를 먹었다. 막상 알고 나면 어렵진 않은데 아예 처음 해보는 작업이어서 적용시킬 때 좀 어려움이 있었다. 약간의 삽질과 함께 좀 더 자킬에 적응해가는 과정이랄까. 그럼 적용 방법 및 겪었던 삽질에 대해서 얘기해보겠다

## disqus란?

disqus는 네트워크 플랫폼을 사용하는 웹 사이트 및 온라인 커뮤니티를 위한 전 세계 블로그 주석 호스팅 서비스라고 한다. 쉽게 얘기해서 댓글 기능을 직접 구현하지 않고 위젯의 형태로 블로그나 웹 사이트에 삽입하여 사용하는 댓글 서비스이다. 보통 포털사이트들의 블로그 말고 웬만한 블로그 사이트들을 보면 포스팅 된 글들의
맨 아래에 달린 댓글 기능이 보통 이 기능이라고 보면 된다. 직접 구현하지 않아도 된다니! 엄청나게 편하지 않은가? 어렴풋이 댓글은 어떻게 구현해야되나 생각하고 있었는데 이런 서비스의 형태로 가능하다니 기분이 좋았다. 직접 구현하는 것은 다른 웹 사이트를 개발할때 해보는 걸로 하고 지킬에는 어떻게 적용 시키는지 알아보자

> Whatever velit occaecat quis deserunt gastropub, leggings elit tousled roof party 3 wolf moon kogi pug blue bottle ea. Fashion axe shabby chic Austin quinoa pickled laborum bitters next level, disrupt deep v accusamus non fingerstache.

