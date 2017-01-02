本程序是使用Python语言实现的NSGA2算法，程序中使用了numpy库

种群个体编码方式：
    实数编码

选择操作：
    NSGA2中快速非支配排序方式
    根据分层号和拥挤距离, 使用锦标赛方式选择
    锦标赛窗口大小为6, 采用硬编码方式写入在程序中
交叉操作：
    使用单点交叉方式
变异操作：
    传统操作的均匀变异方式

特点：
    1.本文考虑多目标函数特点，只修改多目标函数及选择操作中的数值矩阵即可
    2.考虑不同变量的数值范围问题，在主函数中设置了范围向量矩阵
    3.对测试函数实现抽象类继承，不同函数只需要少量更改即可

附加：
    mulObject.py 主函数
    x.py 将运行后的输出格式化 输入到x.txt
    gj.R 将x.txt的结果可视化




