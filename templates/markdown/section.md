{% if name.lower() != "none" %}
## <i class="fa fa-chevron-right"></i> {{ name }}
{% endif %}
{% if legend %}
{{ legend }}

{% endif %}
{% raw  %}
{% block body %}
{{ data }}

{% endblock body %}
{% endraw %}
