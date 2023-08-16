# zhixuewang-python

![](https://img.shields.io/badge/License-MIT-blue) ![](https://img.shields.io/badge/Python-3+-green) ![](https://img.shields.io/pypi/v/zhixuewang)

## 安装

### 使用 pip 安装（推荐）
```bash
pip install zhixuewang
```
### 下载 源码 安装
```bash
git clone https://github.com/anwenhu/zhixuewang
cd zhixuewang
python setup.py install
```

## 简单示例
### 代码
```python
from zhixuewang import login

zxw = login(您的智学网账号, 您的智学网密码)
print(zxw.get_self_mark())
```
### 结果（仅供参考）
```
您的名字-考试名称
语文: 121.0
数学: 121.0
英语: 137.5
理综: 277.0
物理: 101.0
化学: 93.0
生物: 83.0
总分: 656.5
```

**更多高级功能请[查看文档](https://zxdoc.risconn.com)。**



## 问题和建议

如果您在使用的过程中遇到任何问题，或是有任何建议：

① 加入QQ群讨论：862767072（备注：GitHub智学网库）；

② 前往 [Issues](https://github.com/anwenhu/zhixuewang/issues) 进行提问；

如果有其它不常见的功能需求, 可以前往 [MasterYuan418/zxext](https://github.com/MasterYuan418/zxext) 查找或提出
