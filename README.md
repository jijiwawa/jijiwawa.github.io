[TOC]
## PCC 算法流程
### 1
分别获取用户u和v评分了的物品字典，形如：{u:[1,2,3,4,7],v:[2,4,5,6]...}
$I_u$
$I_v$

### 2
#### 2.1
分别获取用户u和v评分了的物品的平均值，形如：{u:3.4,v:1.6,...}
ave_u
ave_v

#### 2.2 
求用户u和v共同评分了的物品集合
$ret_dict = I_u \bigcap I_v$

### 3
判断交集ret_dict是否为空
+ 空
+ 非空
遍历ret_dict计算pcc

### 4 使用的参数
#### 4.1 用户评分的物品表
#### 4.2 用户评分的物品的平均分
#### 4.3 训练矩阵


### python 拓展 C
https://blog.csdn.net/weixin_34226706/article/details/86991937
https://zhidao.baidu.com/question/199567340219173605.html


  
