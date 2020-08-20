---
layout: post
title:  "Running for-loop with multiple parameters"
date:   2020-08-09 #2020-08-19 22:22:51 -0400
last_modified_at:
categories: til
tags: python
---

{{ page.title }}

```python
result= []
for p in 5, 10:
    out = 0
    for _ in range(p):
        out += 100
    result.append(out)
print(result)

> [500, 1000]
```