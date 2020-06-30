<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-github-colors.svg?maxAge=3600)](https://pypi.org/project/django-github-colors/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-github-colors.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-github-colors.py/actions)

### Installation
```bash
$ [sudo] pip install django-github-colors
```

##### `settings.py`
```python
INSTALLED_APPS+ = [
    "django_github_colors",
]
```

#### Examples
```html
{% load github_colors %}

{% github_colors repo.language %}
```

```html
<span class="repo-language-color ml-0" style="background-color:{% github_colors repo.language %}"></span>
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>