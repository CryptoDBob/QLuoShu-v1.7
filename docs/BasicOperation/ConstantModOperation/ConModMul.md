# ConModMul(a, N, qvec1, qvec2, auxadd)
## 定义
### 运算公式
|a*x mod N>
### 运算含义
常数模乘运算(a和N是常数)
## 参数
int **a**：常数

qlist **qvec1** **qvec2**：量子比特数组，保存操作数

qubit **auxadd**：用于QAdder和控制常数模加运算的辅助量子位

int **N**：模数
## 返回值
常数模乘运算结果