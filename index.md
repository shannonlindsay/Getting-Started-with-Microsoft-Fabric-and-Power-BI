---
title: Online Instructions
permalink: index.html
layout: home
---

# Welcome to the best day of the conference - Getting Started with Microsoft Fabric and Power BI

## Meet your instructors! 

- [Stephanie Bruno](https://www.linkedin.com/in/brunostephanie/), Microsoft MVP - Grand High Witch at [Data Witches](https://data-witches.com/)
- [Shannon Lindsay](https://www.linkedin.com/in/shannonrlindsay/), Microsoft Fabric PM, Data Witch
- [Jasmin Simader](https://www.linkedin.com/in/jasmin-simader/) , Microsoft MVP, Data & BI Consultant at Data Therapy
- [Kathrin Borchert](https://www.linkedin.com/in/k-borchert/), Microsoft MVP, Consultant/Founder at YoDaBI

# What's in store 🌙✨

Step into a realm where magic weaves through the fabric of the digital cosmos. Here, you'll find hyperlinks that are like ancient scrolls, each one holding the secrets to today's mystical session.

Should questions arise like whispers in the forest, fear not. Cast your message into the GitHub cauldron or send an owl via email. Our coven is ready to assist on your magical journey.

Begin your adventure below, and may the stars guide your path.

*Translation: Hyperlinks to everything you need to know about today's session are listed below. If you have any questions, you can submit a [GitHub issue](https://github.com/shannonlindsay/Getting-Started-with-Microsoft-Fabric-and-Power-BI/issues/new) or reach out to us via email.*

## Course Links - labs and additional resources 🔮🪄

**[SharePoint Link for Lab Instructions](https://4lbi.sharepoint.com/:f:/s/filesfromYQ/IgA1sPPC5jOtTLQuFuleXWNdAQdp_clMwq6NgzfDFglKfbc?e=VvnaU5)**

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Topic | Link |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
