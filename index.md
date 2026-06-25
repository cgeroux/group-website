---
layout: home
lesson-example: "https://carpentries.github.io/lesson-example"
title: Building Websites in GitHub
---

## Description
{{ site.description }}
{% assign lead=site.team_members | where: "role", "project lead"| first %}
The project is led by {{ lead.name }}
[See our full team](about#team)

Here is an [example lesson]({{ page.lesson-example }}) from software carpentries.

More details about the project availble from the [About page](about.md)

Have any questions about what we do? [We'd love to hear from you!](mailto: {{site.email}} )
