# chapter 2

## 关系数据库的结构

关系数据库由**表（table）**组成，每个表有唯一的名字。

表中的一行代表了一组值之间的一种联系。

**关系实例**表示一个关系的特定实例。

关系模型中：**关系**☞表；**元组**☞行；

## 数据库模式

数据库模式：数据库的逻辑设计；

数据库实例：给定时刻数据库中数据的快照；

## 码

码：区分给定关系中的不同元组的方法；

设R表示关系r模式中的属性集合，若R的子集K是r的一个**超码**，则限制了关系r中任意两个不同的元组不会在K的所有属性上相同；

**候选码**：最小超码；

**主码**（primary key）：数据库中用来区分不同元组的候选码；

一个关系模式$r_1$可能在他的属性中包括另外一个关系模式$r_2$的主码，这个属性在$r_1$上称作参考$r_2$的外码（foreign key）。关系$r_1$也称作外码依赖的参照关系，$r_2$叫做外码的被参照关系；

