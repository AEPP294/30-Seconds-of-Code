---
title: Radians to degrees
type: snippet
language: python
tags: [math]
cover: watermelon-bike
dateModified: 2020-11-02
---

Converts an angle from radians to degrees.

- Use `math.pi` and the radian to degree formula to convert the angle from radians to degrees.

```py
from math import pi

def rads_to_degrees(rad):
  return (rad * 180.0) / pi

rads_to_degrees(pi / 2) # 90.0
```
