# sphinx

+ 输出latex空页过多,在`conf.py`写入
```python
latex_elements = {
    'extraclassoptions': 'openany,oneside',
}
```