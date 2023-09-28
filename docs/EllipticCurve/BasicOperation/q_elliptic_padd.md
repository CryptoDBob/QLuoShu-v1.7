# q_elliptic_padd(p,a,b,P,Q)
## 定义
### 运算公式
P+Q P,Q∈E/F_p:y^2 = x^3+ax+b
### 运算含义
素数域上椭圆曲线点加运算
### 量子线路图
![f1.png](f1.png)
## 参数
int **p** **a** **b**:椭圆曲线参数

vector **P** **Q**：椭圆曲线上的不同点
## 返回值
P+Q的坐标（x，y）的量子态