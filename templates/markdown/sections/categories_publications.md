<h1>{{ name }}
<a class="btn btn-sm btn-primary" role="button" href='javascript:;' onclick="$('.collapse-table.collapse').collapse('show')">Show all</a>
<a class="btn btn-sm btn-primary" role="button" href='javascript:;' onclick="$('.collapse-table.collapse').collapse('hide')">Hide all</a>
</h1>
Click on section title to see details.

{% for type_content in content %}
<h2>
<a data-toggle="collapse" href="#{{type_content.title_id}}" aria-expanded="false" aria-controls="#{{type_content.title_id}}">
<i class="fa fa-chevron-right"></i>
{{type_content.title}}
</a>
</h2>

<div id="{{type_content.title_id}}" class="collapse-table collapse">
{{ type_content.details }}
</div>
<br>
{% endfor %}

<a class="btn btn-sm btn-primary" role="button" href='javascript:;' onclick="$('.collapse-table.collapse').collapse('show')">Show all</a>
<a class="btn btn-sm btn-primary" role="button" href='javascript:;' onclick="$('.collapse-table.collapse').collapse('hide')">Hide all</a>


---

cited as


```txt
@article{llm4eda,
  title   = {Awesome LLM for EDA: A curated paper list of Large Language Models for Electronic Design Automation.},
  author  = {Han, Yaohui},
  journal = {han-0107.github.io/Awesome-LLM-for-EDA},
  year    = {2026},
  url     = {https://han-0107.github.io/Awesome-LLM-for-EDA/}
}
```
