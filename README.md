我有一个H2当我去刷机*shao的固件会没办法正常使用，作者也说了不支持h2，但是为什么和h1同样mcu的也不能用呢，他提到h1配合他的扩展板就可以使用，
因此本章将是我的实验过程。让大众化的h2也能刷他的h3固件。
因此前几天我从朋友那里借到一个h3 mini进行测试。
我发现区别只是在于那几个传感器，其他没什么不同。
貌似我对于这样的破解可能不太道德，哈哈哈
我用了1下午的时间进行测试发现只需要把h2的i2cSDA i2cSCL连接到h3的就可以用他的固件开机，这可真是个惊喜
代表不要代码就可解决，只需要做一个对应的硬件即可。
一开始我考虑直接做一个带有传感器的h2，后来想了想，我干脆做成模块，这样子大家可以一起用，不用换设备
我的过程已经带走了图片文件夹里，如果你没看到，我还没把文档里面的做好，稍等几个小时应该就行了，
我用github不太习惯，不太会玩。哈哈
下面是英文注释
I have an H2 that cannot be used properly when I go to flash the firmware of * shao. The author also said that H2 is not supported, but why can't it be used with the same MCU as H1? He mentioned that H1 can be used with its expansion board,
Therefore, this chapter will be my experimental process. Enable popular H2 to also flash its H3 firmware.
So a few days ago, I borrowed an H3 mini from a friend for testing.
I found that the only difference lies in those few sensors, there is not much difference in others.
It seems that I may not be very ethical about such cracking, hahaha
I spent an afternoon testing and found that just connecting the i2cSDA i2cSCL of h2 to the firmware of h3 can boot it up. This is really a surprise
It can be solved without code, just by creating a corresponding hardware.
At first, I considered making an H2 with sensors directly, but later on, I decided to make it a module so that everyone can use it together without changing devices
My process has already taken away the image folder. If you haven't seen it, I haven't finished the document yet. Just wait a few hours, it should be fine,
I'm not used to using GitHub and I'm not very good at playing it. ha-ha
