## R语言数据可视化之美
### 目录
#### 一、数据预处理
#### 二、类别比较型图表
#### 三、数值关系型图表
#### 四、数据分布型图表
#### 五、时间序列型图表
#### 六、局部整体型图表
#### 七、高维数据可视化
#### 八、层次关系型图表
#### 九、网络关系型图表
#### 十、地理空间型图表
***
一、数据预处理
* as,numeric()向量变成数值
* as.character(）向量变成字符型
* 导入：x<-read.table(file.choose(),header=T,stringsAsFactors=FALSE)
* 导出：write.csv(x,file="xxx.csv")
* Tips:尽量使用一维数据列表数据框，或者用reshpe2包的melt（）

缺失值处理：tydyr包
> 缺失值处理时，excel中的分隔符号是\t
