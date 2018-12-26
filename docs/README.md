## Dom's Performance Notes

# Java Blogs
<ul>
  {% for post in site.posts %}
    {% if post.tags contains 'java' %}
        <li>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} </a>
        </li>
    {% endif %}
  {% endfor %}
</ul>

# donet Blogs
<ul>
  {% for post in site.posts %}
  {% if post.tags contains 'dotnet' %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} </a>
    </li>
    {% endif %}
  {% endfor %}
</ul>