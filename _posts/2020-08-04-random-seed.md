---
layout: post
title:  "Reproduce a random number"
date:   2020-08-04 #2020-08-19 22:22:51 -0400
last_modified_at:
categories: til
tags: python
---

{{ page.title }} in python by using the same seed.

```python
import random
random.seed(1234)
random.random() # first random number
random.seed(1234)
random.random() # second random number
```