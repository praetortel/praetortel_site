---
title: Links
layout: default
---
Here are some links of some people or things I really like. Feel free to pay them a visit, and let them know Praetor sent you!

Also, you can find my personal site [here](https://praetor.sdf.org)

<ul>
    {% for site in site.data.links %}
      <a href="{{ site.url }}"><li>{{ site.name }}</li></a>
    {% endfor %}
  </ul>