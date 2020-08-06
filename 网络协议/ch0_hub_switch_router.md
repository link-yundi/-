## hub/switch/router的区别

- Hub 集线器

> 单集线的作用是把<font color=red>内网</font>中的网络设备连接起来，它不会过滤数据，也没有关于数据应该发向哪里的智能。当一个端口收到数据之后，它会将数据<font color=red>广播到所有的连接设备</font>上。
>
> <img src="hub.jpg" alt="hub " style="zoom:33%;" />

- Switch 交换机

> Switch 能够解析连接在端口的设备的物理地址(MAC地址)，并把这些地址存到一张表中记录，所以当一个数据包发送到一个交换机，它只会被发往<font color=red>指定的目标端口</font>
>
> <img src="switch.jpg" alt="switch " style="zoom:33%;" />
>
> <img src="switch_1.jpg" alt="switch_1 " style="zoom:33%;" />
>
> **diff between hub and switch**
>
> <img src="hub_switch.jpg" alt="hub_switch " style="zoom:40%;" />

- Router 路由器

> Hub & switch只能用于内网的数据传输，而不能用于外网。因为和外网进行数据通信需要读取IP地址。
>
> <img src="about_router.jpg" alt="about_router " style="zoom:40%;" />
>
> 当路由器接受到一个数据包后，它会解析IP是它自己的ip还是其他网路的ip，如果是自己的，就自己留着，如果的别的，就转发出去
>
> <img src="router_data.jpg" alt="router_data " style="zoom:33%;" />
>
> 
>
> <img src="router_2.jpg" alt="router_2 " style="zoom:33%;" />

----------

**hub & switch是用于内网的，router是用于外网的**

> <img src="router_3.jpg" alt="router_3 " style="zoom:33%;" />

