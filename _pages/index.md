---
layout: page
title: Home
id: home
permalink: /
---

# 今承达·合同管理使用手册 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  查看我们的<span style="font-weight: bold">[官网](www.jincenda.com)</span>来更好地了解我们的产品。
</p>

本教程分为以下几个部分：

- [[前期准备]]
- [[合同起草]]
- [[合同审批]]
- [[合同台帐]]
- [[合同履行]]
- [[合同报表]]
- [[基础]]

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
