# 关于 我


---
{{ $image := .Resources.GetMatch "1.gif" }}
<img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}">
---


