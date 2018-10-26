# About Us 
The Queer Ecology Research Cluster meets every other week to investigate how sexuality and concepts of nature have been historically linked. In particular, we are interested in how evolutionary and ecological science has informed what is "natural" and how we use this information to delineate certain sexual behaviors as normal or aberrant. Queer Ecologies seeks to examine the historical making of the natural as it relates to sexuality while communicating the overwhelming diversity of sex and gender in biology. 

{% for post in site.posts %}
  [{{ post.title }}]({{post.url}})
  {{ post.content }}
{% endfor %}
