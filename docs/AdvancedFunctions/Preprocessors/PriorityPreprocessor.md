# 优先级

优先级处理器能够管控脚本加载优先级。

## 如何开启
在脚本中添加 `#priority number` 即可设定优先级，`number` 即为逆向设定的优先级。

## 有什么用
优先级越高的脚本，越早能够被加载。  
优先级相同的脚本将按路径名的字母顺序排序，再次决定优先级。