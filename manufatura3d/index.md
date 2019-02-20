---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div>
    {% for pessoa in site.pessoas %}
        <a href="{{ pessoa.url }}">  {{ pessoa.nome }} </a>
    {% endfor %}
</div>