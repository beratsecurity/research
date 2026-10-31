# SecNotes

Siber güvenlik araştırmaları — GitHub Pages (Jekyll).

## Yapı

```
_config.yml           # Site ayarları
index.html            # Araştırma listesi (ana sayfa)
_layouts/             # Şablonlar
_posts/               # Araştırmalar (YIL-AY-GUN-baslik.md)
assets/css/style.css  # Tema
```

## Yeni araştırma ekleme

`_posts/` içine `2026-11-01-baslik.md` oluştur:

```markdown
---
title: "Başlık"
date: 2026-11-01
description: "Kısa açıklama."
---

İçerik...
```

## Yerelde çalıştırma (opsiyonel)

```bash
bundle install
bundle exec jekyll serve
```
