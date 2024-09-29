## 2.1 使用真实数据

- 流行的开放数据存储库

  - UC Irvine Machine Learning Repository
  - Kaggle datasets
  - Amazon's AWS datasets
- 元门户站点

  - Data Portals(https://dataportals.org/)
  - OpenDataMonitor
  - Quandl
- 其他一些列出许多流行的开放数据存储库的使用

  - Wikipedia's list of Machine Learning datasets
  - Quora.com
  - The datasets subreddit

## 2.2 观察大局

- 范数指标越高，它越关注大值而忽略小值。这就是RMSE对异常值比MAE更敏感的原因。但是，当离群值呈指数形式稀有时（如钟形曲线)，RMSE表现非常好，通常是首选。

```shell
$python -m pip --version

$python -m pip install --user -U pip

$python -m pip install -U jupyter matplotlib numpy pandas scipy sckit-learn

# 如果你创建了virtualenv，则需要注册到Jupyter并给他一个名字
$python -m ipykernel install --user --name=python3

$jupyter notebook
```

![1727571255165](image/readme/1727571255165.png)
