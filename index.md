---
title: "Inicio"
layout: default
---

# 👋 Bienvenido a Zaira Dev

Soy Zaira, una apasionada del desarrollo de software y la inteligencia artificial. En este espacio compartiré artículos, tutoriales y reflexiones sobre tecnología.

## 📌 Temas principales
- 💻 Desarrollo de software
- 🤖 Inteligencia Artificial y Machine Learning
- 🔧 Buenas prácticas y herramientas para programadores
- 🚀 Innovación y tecnología aplicada

## 📢 Últimos artículos
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d %b %Y" }}
{% endfor %}

---

📬 **¿Quieres estar al día?** Sígueme en [LinkedIn](https://www.linkedin.com/in/zrubio) para más contenido. 😊
