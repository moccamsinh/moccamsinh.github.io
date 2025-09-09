---
layout: default
title: Mộc Cảm Sinh
---

<link rel="icon" href="/favicon.ico" type="image/x-icon">

Là một thân sống sinh ra từ ba nhánh cảm thức. Không khuôn phép, không cao siêu, chỉ cần một người đủ lặng – đã có thể thấy mình trong đó.

- Là *mạch sống* – nơi dòng lực âm thầm chảy, khiến ta còn muốn sống, muốn đi, muốn trở thành điều gì đó có nghĩa.
- Là *lối nhẹ* – bước đi không tranh đoạt, không níu giữ, để mỗi ngày trôi qua đều thảnh thơi mà sâu.
- Là *ý chạm* – khoảnh khắc một hình ảnh, một câu nói, hay một làn gió khẽ lướt – cũng có thể làm tim rung, và đời đổi.

Mộc cảm sinh không phải để thuyết giảng.
Nó để sống cùng. Để lớn lên cùng. 
Như một nhành cây – không gấp, không vội, nhưng chắc chắn sẽ vươn.

<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%d-%m-%Y" }})</small>
    </li>
  {% endfor %}
</ul>

— muziii
