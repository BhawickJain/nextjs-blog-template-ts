---
title: "Dreamliner"
date: "2022-09-07"
---

![Dreamliner Safety at Stake](https://drive.google.com/uc?export=view&id=1NYUfS5DJ8DzosN3-RW6q6IFaDVbk-Uhv)

Next.js has two forms of pre-rendering: **Static Generation** and **Server-side Rendering**. The difference is in **when** it generates the HTML for a page.

- **Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js let's you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.
