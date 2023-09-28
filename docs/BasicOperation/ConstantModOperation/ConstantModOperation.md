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
# ConModaddmul(a, N, qvec1, qvec2, auxadd)
## 定义
### 运算公式
|b+a*x mod N>
### 运算含义
常数乘法和模加法运算(a和N是常数)
## 参数
int **a**：常数

qlist **qvec1**：量子比特数组，保存操作数x

qlist **qvec2**：量子比特数组，保存操作数b

qubit **auxadd**：用于QAdder和控制常数模加运算的辅助量子位

int **N**：模数
## 返回值
常数乘法和模加法运算结果

# ConModExp(a, N, qvec1, qvec2, qvec3, auxadd)
## 定义
### 运算公式
|a^x mod N>
### 运算含义
常数模幂运算(a和N是常数)
## 参数
int **a**：常数

qlist **qvec1** **qvec2** **qvec3**：量子比特数组，保存操作数

qubit **auxadd**：用于QAdder和控制常数模加运算的辅助量子位

int **N**：模数
## 返回值
常数模幂运算结果