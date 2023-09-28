# ConModAdd(a, N, qvec, auxadd)
## 定义
### 运算含义
使用量子傅里叶转换进行常数模加运算
### 运算公式
|a+x mod N>
## 参数
int **a**：操作数a

qlist **qvec**：量子比特数组

qubit **auxadd**：用于QAdder和控制常数模加运算的辅助量子位

int **N**：模数
## 返回值
常数模加运算结果