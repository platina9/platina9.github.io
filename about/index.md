---
title: 關於
layout: page
comments: no
---

{{ site.about }}

----

###聯繫方式：

{% if site.qq %}
ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
{% endif %}
網站：[{{ site.name }}]({{ site.url }})

電郵：[{{ site.email }}](mailto:{{ site.email }})

----


[![新浪微博](http://service.t.sina.com.cn/widget/qmd/{{ site.weibo }}/f78fbcd2/1.png)](http://weibo.com/u/{{ site.weibo }})
