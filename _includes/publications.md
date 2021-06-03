{% for panel in include.panels %}
    ###**{{ panel.title }}**
    {{ panel.detail }}
    [Read More]({{ panel.link }})
{% endfor %}
