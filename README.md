# ZyzApWifi
用于物联网AP模式下配网
本人从事物联网行业也有一段时间了，之前在北京实习的时候，公司用过汉枫的wifi模块、小e的8266以及现在公司用的庆科模块，很多时候我们会用到的一种配网方式叫做
smartLink 或者smartconfig 其实这种配网的方式原理都是基于UDP，大家肯定了解UDP的特性，所以这种配网效果一致不是很理想，所以我在这里推荐大家使用
AP模式配网，通过发现这种效率很高，点对点的传输Wi-Fi名称和密码一般情况下都能成功，当然现在做的好的物联网配网模式有AP＋超声波配网，多一层保障，
这样配网效率大大提高了
1.使用效果 
使用这个本项目可以给你带来什么神奇效果了？
假定我们有这么一个场景：1.采用AP模式配网 2.在配网的过程第一步需要硬件开启配网模式也就是打开wifi模块的AP模式 3.然后app获取当前的周围的wifi列表，
去选中硬件设备的AP并连接上去（当然需要输入密码）4.发送需要给wifi模块配网的wifi名称和密码（当然你肯定要能搜得到的wifi，不然一切都是扯淡）5.如果第四部的
信息发送无误那么wifi模块就能够配网成功
上面我总结了AP配网的流程，估计你们可能会想，这么复杂啊，那用户用起来岂不是很复杂，又连接ap，又要给Ap输入密码，然后还要输入需要配网的wifi名称和密码，
到底是那一个wifi，什么时候连接什么wifi，好了到这里你的app客户已经蒙了。不过不必担心，我已为你们剩下了这下繁琐的操作，你只需要然后用户选择一下需要
配网的wifi和输入其对应的密码，那么再点击一下发送信息的按钮就搞定了
2.How to 用 (不要笑我哈，我英文不好)
