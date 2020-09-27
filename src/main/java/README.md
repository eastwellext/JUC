synchronized 关键字
锁升级，偏向锁，自旋锁，重量级锁。


volatile 关键字


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

ReentrantLock(true) 公平锁