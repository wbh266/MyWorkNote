
底层各个硬件模块使用不同的通信接口,涉及不同的总线协议（can\lin\tcp/ip），
* pdur理解为通信服务层的中间件，pdur是一个基本软件模块，依赖于我们设计好的文件（比如CAN通信矩阵、产出的DBC文件等配置文件）在设计ECU时自动生成。
    对于上层下发的数据，通过设定的路由规则将数据分配到相应的协议总线上；对下接口就涉及到CAN TP/IF、LIN TP/IF、DoIP等。
    对于要上传方向的数据，将不同协议统一成一致数据包上传，进一步通过pdum将pdur打包的数据包与AppFramwork中的信号建立API接口，实现与上层应用程序的数据交互。
