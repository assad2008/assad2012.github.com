---
layout: page
title: 欢迎来到我的Github主页
tagline: 你好
---
{% include JB/setup %}

## 关于我
-------------------------------------------

余诞于中华人民共和国三十六年甲申月辛卯日(农历乙丑年)，家道贫，世累耕。自幼喜好读书，经史子集，皆有喜好之。幼习书法，不成气候，少学古文，小有成就。八岁入学，十二求学他乡，恍惚十余年已过，思前之事，若过眼云烟，感慨万千。天道不泯，吾心尚在。虽穷而志坚，虽微而心广！今年方廿八，却无建树，碌碌无为，吾心当愧！呜呼！时乖命謇，命运不济，虽心存济世之愿，却无襄民之时。不知何时方登龙庭，造福于民，恩济天下，虽有此意，却无命运，但苍天有愿，助吾成功！

- River Locker King is my English name & Chinese name is Wang Jiang.
- Shaanxi Province China
- Pythoner And PHPer
- I am like Reading,Historian,Literature,etc.
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



