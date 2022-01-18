# QThread 创建多线程

## 单线程程序

+ 对于只有一个线程的程序，操作是顺序执行的，如果有某个比较耗时的计算和操作，就容易造成堵塞

## QThread

> QThread 是库类

+ QTHread类提供管理线程的方法
  + 一个对象管理一个线程
  + 一般从QThread继承一个自定义类，重载run函数


+ [source](https://subingwen.cn/qt/thread/)

### 创建QThread

+ 父类和父对象不一样
  + 父类是继承关系
  + 父对象是从属关系
    + QT维护了一个对象树，用于对象回收（析构，不一定是继承）

### 常用函数

+ isFinished： 判断当前线程中的任务是否处理完毕了
+ isRunning:   判断子线程是否在执行任务，与isFinished相对应
+ setPriority： 设置优先级，枚举类型，优先级越低，抢到CPU执行时间的概率就越低
+ exit
+ wait

### 信号槽 

#### 信号（signal）

+ finished
+ started

#### 槽函数（slot）

+ quit
+ start
+ terminate

#### 静态函数

+ currentThread
+ 休眠函数

#### 任务处理函数

+ [virtual protected] void QThread::run();