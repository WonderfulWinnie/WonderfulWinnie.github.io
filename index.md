<img src="/assets/Mountain_Corgi-min.jpg" width=auto height=auto>

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
