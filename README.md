# README

[youtube video thumbnail images](https://stackoverflow.com/questions/2068344/how-do-i-get-a-youtube-video-thumbnail-from-the-youtube-api):

```
https://img.youtube.com/vi/7cqYiUmutGI/maxresdefault.jpg
```

imgur gifv 

```html
<video loop controls>
	<source src="//i.imgur.com/hpMnPKj.mp4" type="video/mp4">
</video>
```

Maybe for later use

```html
{% if post.cover %}
	<img src="/photos/webp/{{ post.cover }}.webp" alt="{{ post.title}}" class="post-image">
{% endif %}
```
