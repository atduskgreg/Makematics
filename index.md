---
layout: default
---
{% include JB/setup %}

<div id="content" class="span-14">

<div id="posts">

  {% for post in site.posts %}
    <div span="post">
      <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>

      <p class="date"><em>{{ post.date | date_to_long_string }}</em></p>
      {{post.content}}
    </div>  
  {% endfor %}

</div>
</div>

{% include themes/makematics/sidebar.html %}
