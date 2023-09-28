# VarModDou(qvec, aux, N)
## 定义
### 运算公式
|2x mod N>
### 运算含义
计算变量的二倍模乘运算
### 量子线路图
![f6.png](f6.png)
## 参数
qlist **qvec**：存储操作数x

qubit **aux**：控制常数模加运算的辅助量子位

int **N**：模数
## 返回值
VarModDou.QCircuit