---
title: "关于 我"
date: 2019-08-02T11:04:49+08:00
draft: false

lightgallery: true

math:
  enable: true
---

---
{{ $image := .Resources.GetMatch "1.gif" }}
<img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}">
---

