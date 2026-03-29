---
layout: default
title: Mộc cảm sinh
---

<link rel="icon" href="/favicon.ico" type="image/x-icon">

Có ba điều âm thầm lớn lên trong đời sống của một người:
một *lối* để đi, một *mạch* để sống, và những *chạm* để nhớ rằng mình đang sống.

Mộc cảm sinh là nơi ba điều ấy gặp nhau.

<ul>
  {% for post in site.posts reversed %}
    {% unless post.title contains 'ý chạm i' or post.title contains 'ý chạm ii' or post.title contains 'ý chạm iii' or post.title contains 'ý chạm x' %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%d-%m-%Y" }})</small>
    </li>
    {% endunless %}
  {% endfor %}
</ul>

— [muziii](mailto:muz@moca.si)
