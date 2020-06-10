---
layout: post
title: "Defer Iframe Video Youtube Pada Blog Github Pages"
subtitle: "Dengan defer iframe pada blog maka loading blog menjadi ringan."
description: "Dengan defer iframe video Youtube dimaksudkan agar loading iframe tidak mengganggu loading blog."
date: 2016-06-06
author: "Ihsan gunawans"
tags: [ GithubPages, Markdown ]
header-img: "img/post/defer-iframe.jpg"
image: "img/post/defer-iframe.jpg"
social-js: "https://cdn.ampproject.org/v0/amp-social-share-0.1.js"
iframe-js: "https://cdn.ampproject.org/v0/amp-iframe-0.1.js"
accordion-js: "https://cdn.ampproject.org/v0/amp-accordion-0.1.js"
youtube-js: "https://cdn.ampproject.org/v0/amp-youtube-0.1.js"
---

Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf.

Silahkan simpan kode javascript di bawah ini di atas kode `</body`, silahkan buka **_includes** >> **footer.html** dan simpan di paling bawah.

```html
<script>
function init() {
    var vidDefer = document.getElementsByTagName('iframe');
    for (var i = 0; i < vidDefer.length; i++) {
        if (vidDefer[i].getAttribute('data-src')) {
            vidDefer[i].setAttribute('src', vidDefer[i].getAttribute('data-src'));
        }
    }
}
window.onload = init;
</script>
```
Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf.

Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf.

**Kode embed awal**

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/zBASI-CQxw4" frameborder="0" allowfullscreen></iframe>
```

Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf.

```html
<iframe width="560" height="315" data-src="https://www.youtube.com/embed/zBASI-CQxw4" frameborder="0" allowfullscreen></iframe>
```

**Live Demo**

Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf, Ini Adalah Kumpulan Kata-Kata Yang Yang Membentuk Paragraf.
