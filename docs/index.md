---
layout: default
title: Home
---

# Welcome to My Personal Website

![Profile Picture](/assets/profile-picture.jpg)

Hey there! I'm [Your Name](https://yourwebsite.com/about), and this is my personal website. I use this space to share my thoughts, projects, and experiences with the world.

## About Me

I'm a [job title] passionate about [your interests]. I enjoy [hobbies] in my free time and [more about your personality or background].

## Latest Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Projects

Here are some of my recent projects:

- [Project 1](/projects/project1)
- [Project 2](/projects/project2)

## Contact Me

Feel free to reach out to me via [email](mailto:youremail@example.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile).

---
