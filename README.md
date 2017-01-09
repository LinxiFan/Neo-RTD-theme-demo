# Neo-RTD-theme for Sphinx

Online demo [here](https://linxifan.github.io/Neo-RTD-theme-demo). 

Please refer to [LinxiFan/Sphinx-theme](https://github.com/LinxiFan/Sphinx-theme) for more information. 

```bash
$ pip install sphinx-theme
```

In your `conf.py` file:

```python
import sphinx_theme
html_theme = "neo_rtd_theme"
html_theme_path = [sphinx_theme.get_html_theme_path('neo-rtd-theme')]

# All available themes:
print(sphinx_theme.THEME_LIST)
# >> ['stanford_theme', 'neo_rtd_theme']
```
