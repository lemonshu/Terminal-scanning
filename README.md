# Terminal-scanning
利用nmap软件进行端口扫描
Nmap是一个网络连接端扫描软件，用来扫描网上电脑开放的网络连接端。确定哪些服务运行在哪些连接端，并且推断计算机运行哪个操作系统。它是网络管理员必用的软件之一，以及用以评估网络系统安全。
Nmap基本语法如下所示，主要包括扫描类型、选项及扫描目标几个部分组成，Nmap支持的扫描类型有十几种，主要包括TCP SYN扫描、TCP connect扫描、UDP扫描等；扫描目标说明为扫描目标如主机、网络等提供了灵活的表示方法，因此在Nmap命令中，可以使用CIDR、文件等表示扫描目标
首先我把目标设为我本机的IP地址，在nmap输出下有以下内容
加载了148个扫描脚本、14点45分启动SYN隐形扫描，以及发现了若干个开放端口
然后我尝试对百度首页ip进行扫描，显示在15:38完成NSE，0.00s在15:38开始启动NSE
发送了8个原始数据包，接收到了0个。
