# Fabric-
搭建fabric网络的学习笔记
步骤一:决定网络配置


步骤二:为资源设置一个集群

Kubernetes 具有许多有用的工具，使其成为部署和管理 Fabric 网络的普及容器管理平台。（似乎是新增加的平台？之前只有docker）

步骤三:设置 CA

CA需要被首先布置。根 CA 的泄露会导致整个信任域（管理员、节点和它为其生成的任何证书的 CA）崩溃，因此中间 CA 是一种限制根 CA 暴露的有用方法。

步骤四:使用CA创建身份和MSPs
步骤五:部署peer和an ordering node

