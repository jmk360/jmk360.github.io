---
title:  "1 : [Jekyll] 블로그 포스팅 연습"
excerpt: "블로그 포스팅 연습"
categories:
  - Blog
tags:
  - [Blog, jekyll, Github]
date: 2022-10-10
last_modified_at: 2022-10-10

layout: single
classes: wide
toc: true
toc_sticky: true
author_profile: false
sidebar_main: true
sidebar:
  nav:
# search: false
---

# 와우

## 이미지 목차

### 이미지 세부 목차1
![](/images/2022-10-10-first-post/sample.png)
### 이미지 세부 목차2
테스트2
### 이미지 세부 목차3
테스트3

# 코드 추가

```python
for i in range(1, 10):
  for j in range(1, 10):
    print('{} * {} = {}'.format(i, j, i*j))
  print('='*10)
```

# 공지사항 추가

**[공지사항]**[구글](https://www.google.com)
{: .notice--danger}

## 여러줄 공지사항 추가
<div class="notice--success">
<h4>공지사항입니다.</h4>
<ul>
    <li>공지사항 순서1</li>
    <li>공지사항 순서2</li>
    <li>공지사항 순서3</li>
</ul>
</div>

# 버튼 추가

[구글](https://www.google.com){: .btn .btn--danger}

# youtube 영상 추가
{% include video id="V5kFzKkRSLw" provider="youtube" %}