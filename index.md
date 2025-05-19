---
layout: home
title: "Marc Xará | Artist Portfolio"  # Título da página
permalink: /  # Garante que seja a página inicial
---

# Olá, eu sou o Marc!  

**Designer gráfico e ilustrador** com foco em branding e estampas.  

## Últimos Projetos  
{% raw %}
{% for project in site.portfolio limit:3 %}  
- [{{ project.title }}]({{ project.url }})  
{% endfor %}
{% endraw %}

[Ver portfólio completo](/portfolio) | [Contato](/contact)