# Ct_PointADD(vx1,vy1,x2,y2,p,n2,ctrl)
## 定义
椭圆曲线控制点加运算
## 参数
int **p** **x2** **y2**:椭圆曲线参数

qlist **vx1** **vy1**:n2量子比特数组

int **n2**:ceil(log(p, 2))+1

vector **P** **Q**：椭圆曲线上的不同点

qubit **ctrl**：控制辅助量子比特
## 返回值
椭圆曲线控制点加运算计算结果
