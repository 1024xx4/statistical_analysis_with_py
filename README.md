# Python で理解する統計解析の基礎

## 作中の関数

### `np.histogram`
度数を求める時に使用

###### Library
`NumPy`

---

######引数:

- bins: 階級数(int)
- range: 最小値と最大値(tuple)

### `np.cumsum`
累積和の計算に使用

###### Library
`NumPy`

---
### `np.cov`
共分散を求める。
ただし、返値は、共分散行列（covariance matrix）または、分散共分散行列（variance covariance matrix）と呼ばれる行列
###### 引数：
- ddof(delta degree of freedom): デルタ自由度
###### Library
`NumPy`

---
### `np.corrcodf`
相関係数を計算できる。戻り値は相関行列(correlation matrix)
##### Library
`NumPy`

---
### `.scatter`
散布図を描画できる

###### 引数
- 第１引数: x軸の Data
- 第２引数: y軸の Data

###### Library
`MatplotLib`
