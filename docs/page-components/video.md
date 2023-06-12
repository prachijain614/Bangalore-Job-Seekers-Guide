---
layout: page
title: Video
subtitle: Page Components
menubar: docs_menu
show_sidebar: false
toc: true
redirect_from: 
    - /page-with-video/
---

## Example

{% include youtube.html video="iRuJufELrWo" starttime=10 endtime=15 %}

## YouTube

To embed the YouTube video, include the youtube.html where you want the video to appear and then pass in the YouTube id as the video variable. 

{% include youtube.html video="iRuJufELrWo" starttime=10 endtime=15 vtitle="This is a demo video" description="Jekyll Video Demonstration for my project" category="Education" requiresSubscription="Free" %}



{% raw %}
```liquid
{% include youtube.html video="videoid" %}
```
{% endraw %}

### Start Time

You can optionally include a start time in seconds. This works the same as the ?t= parameter in Youtube URLs.

{% raw %}
```liquid
{% include youtube.html video="videoid" starttime=10 endtime=15 %}
```
{% endraw %}


## Vimeo Video

It is also possible to embed Vimeo videos in a similar way by including the vimeo.html and passing in the video id.

{% raw %}
```liquid
{% include vimeo.html video="videoid" %}
```
{% endraw %}
