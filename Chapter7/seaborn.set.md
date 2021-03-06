# seaborn.set

```python
seaborn.set(context='notebook', 
            style='darkgrid', 
            palette='deep', 
            font='sans-serif', 
            font_scale=1, 
            color_codes=True, 
            rc=None)
```

一步设定自定义图表参数。

每个参数可以被直接或者间接设定，参见下方的引用参数以获取更多信息。

参数：context：字符串或者字典

> 绘图上下文参数，参见[`plotting_context()`](https://github.com/apachecn/seaborn-doc-zh/blob/master/docs/seaborn.plotting_context.html#seaborn.plotting_context)

style：字符串或者字典

> 坐标轴样式参数，参见[`axes_style()`](https://github.com/apachecn/seaborn-doc-zh/blob/master/docs/seaborn.axes_style.html#seaborn.axes_style)

palette：字符串或者序列

> 调色板，参见[`color_palette()`](https://github.com/apachecn/seaborn-doc-zh/blob/master/docs/seaborn.color_palette.html#seaborn.color_palette)

font：字符串

> 字体，参见 matplotlib 字体管理

font_scale：浮点数，可选的

> 独立缩放因子，以独立缩放字体元素的大小。

color_codes：布尔值

> 如果为真并且调色板是一个 seaborn 调色板，重新映射速记颜色代码（比如，"b"，"g"，"r"，等等）到调色板上的颜色。

rc：字典或者 None

> rc 参数字典映射以覆盖以上参数。