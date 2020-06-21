# UN01's Website.

# My Projects
<ul>
<li><a href="https://github.com/aUN01forC4739/HelloWorldPublic">Hello World Project Repo</a></li>

<li><a href="https://github.com/aUN01forC4739/aUN01forC4739.github.io">Github Website Project Repo</a></li>
</ul>

# My Interests
I'm interested in learning about computer science!

# My Blog
I'm really exited to blog my journey on GitHub.com.

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

# Get in Touch
<ul>
<li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>

<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
