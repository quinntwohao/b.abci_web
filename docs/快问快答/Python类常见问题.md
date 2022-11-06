

# 🚠 Python 常见问题小知识

## python如何将一一对应的关系组合成字典,或者两个列表组合成字典?

将两个列表组合成字典

邮编功能在python中有很多优点。 使用zip函数，我们可以从两个列表创建字典。

```
list_1 = ["One","Two","Three"] list_2 = [1,2,3] dictionary = dict(zip(list_1, list_2)) print(dictionary)

输出量

{'Two': 2, 'One': 1, 'Three': 3}
```


关于“python如何将两个列表组合成字典”这篇文章就分享