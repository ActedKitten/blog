---
layout: default
---

# 欢迎来到 Sojo's BLOG 👋

这是我的个人博客，分享技术、想法和生活感悟。

---

## 📝 最新文章

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
**发布于：** {{ post.date | date: "%Y年%m月%d日" }}

{{ post.excerpt }}

[阅读全文 →]({{ post.url }})

---
{% endfor %}

## 🔗 快速链接

- [关于我](./about.html)
- [GitHub](https://github.com/ActedKitten)
- [主站点](https://actedkitten.github.io)

---

## 关于我

Hi，我是 Sojo（ActedKitten）。在这里分享我的学习笔记、项目经验和技术见解。

*最后更新：2026年8月*