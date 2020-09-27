synchronized 关键字
锁升级，偏向锁，自旋锁，重量级锁。
饿汉模式，懒汉模式，双重检测。


volatile 关键字
线程间的可见性
可以禁止指令重排序

cas(期望值，更新值)
无锁，即乐观锁


AtomicInteger
incrementAndGet()方法；

效率上
long
AtomicLong
LongAdder


synchronized 本身就是可重入锁。

synchronized 修饰方法，和synchronize this是一个效果
都是锁本身这个对象。

可重入锁
ReentrantLock(true) 公平锁

CountDownLatch

CyclicBarrier 用在限流场景不合适
复杂操作
 -数据库
 -网络
 -文件
并发执行
 -不同线程，执行不同的操作

限流场景
Guava RateLimiter


Phaser
bulkregister
arriveAndAwaitAdvance
arriveAndDeregister
重写方式
onAdvance方法，是在栅栏被推倒时自动调用。

ReadWriteLock
共享锁
排他锁

Semaphore
限流

fixthreadpool 固定的线程个数。
semaphore的acquire 可以有 很多个不定个数的线程 同时acquire.

车道和收费站

Semaphore(2, true) 公平，即排队。

都是用AQS实现的。
AbstractQueuedSynchronizer



