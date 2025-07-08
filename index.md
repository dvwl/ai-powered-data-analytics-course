# AI-Powered Data Analytics Foundation Course

These hands-on exercises are designed to support the AI-Powered Data Analytics Foundation Course by Carbon GPT Sdn Bhd.

## Course Overview

In today's data-driven business environment, the ability to analyze and interpret data is crucial for making informed decisions. This comprehensive course takes participants on a structured journey from basic Excel operations to Python programming for data analysis, incorporating cutting-edge AI tools that are revolutionizing how we work with data.

## Software Requirements

To complete these exercises, you'll need:
- **Microsoft Excel** (for Module 1)
- **DB Browser for SQLite** (for Module 2) - Download at [https://sqlitebrowser.org/](https://sqlitebrowser.org/)
- **Visual Studio Code (VS Code)** and **Python Extension** (for Modules 3-5)
- **AI Tools**: Access to ChatGPT, Claude, or similar AI assistants

You can download VS Code at [https://code.visualstudio.com/](https://code.visualstudio.com/).

## Course Modules

{% assign labs = site.pages | where_exp:"page", "page.url contains '/modules'" %}
| Module | Title | Tools |
| ------ | ----- | ----- |
{% for activity in labs  %}| {{ activity.url | split: '/' | last | split: '-' | last | split: '.' | first | capitalize }} | [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) | {% if activity.url contains 'module-1' %}Excel{% elsif activity.url contains 'module-2' %}SQLite, DB Browser{% else %}Python, AI Tools{% endif %} |
{% endfor %}
