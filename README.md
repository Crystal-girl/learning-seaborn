# learning-seaborn
将复杂、无序的数据转化为图形式进行展示，学习、掌握seaborn，能够更加清晰、直观的了解数据的本质！
## Relational plots
> relplot: 修改两处参考代码错误，并针对错误的产生原因给出解答。
* #1: .tight_layout => .fig.tight_layout
* #2: 增加 dashes 参数设置

> scatterplot: 修改一处参考代码错误。
* #1: 增加 legend 参数设置

> lineplot: 修改三处参考代码错误。
* #1; lineplot(flights_wide) => lineplot(data=flights_wide, dashes=dashes)
* #2: 增加 dashes 参数设置
* #3: 修改 palette 参数设置
