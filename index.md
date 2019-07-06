# Things I Like
- Snowboarding is one of my favorite Hobbies
- I am also enjoying learning to do some coding
- Arduino is fun!

# My Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


# Get in Touch
<ul>
<li><a href="https://twitter.com/{{site.twitter_username}}" target="new">Twitter</a></li>
<li><a href="https://github.com/{{site.github_username}}" target="new">GitHub</a></li>
</ul>
