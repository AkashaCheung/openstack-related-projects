# openstack社区项目介绍

## [openstack主页](https://github.com/openstack)

| 项目名称 | 描述 |
|:---:|:---:|
| [nova](https://github.com/openstack/nova) | openstack中的计算组织控制器，支持多种虚拟化技术(如KVM，LXC等)，对应于AWS的EC2服务 <br> python客户端：[python-novaclient](https://github.com/openstack/python-novaclient)|
| [swift](https://github.com/openstack/swift) | openstack中的非结构化、弹性可伸缩、高可用的分布式对象存储服务，对应于AWS的S3服务 <br> python客户端：[python-swiftclient](https://github.com/openstack/python-swiftclient) <br> swift的benchmark工具：[swift-bench](https://github.com/openstack/swift-bench) |
| [horizon](https://github.com/openstack/horizon) | 基于Django实现，是openstack各个服务的web操作和查看面板，并且结构可扩展，很方便添加新的服务界面 |
| [neutron](https://github.com/openstack/horizon) | openstack的网络组织控制器，提供云计算环境下的虚拟网络功能 <br> python客户端：[python-neutronclient](https://github.com/openstack/python-neutronclient) |
| [marconi](https://github.com/openstack/marconi) | openstack的消息队列服务，对应于AWS的SNS和SQS <br> python客户端：[python-marconiclient](https://github.com/openstack/python-marconiclient) |
| [ceilometer](https://github.com/openstack/ceilometer) | openstack中的事件收集服务，为监控和计费提供支持，这些事件包括平台中用户的资源使用情况和资源的健康状态 <br> python客户端：[python-celiometerclient](https://github.com/openstack/python-ceilometerclient) |
| [cinder](https://github.com/openstack/cinder) | 为openstack平台提供volume卷管理和虚拟块设备服务，对应于AWS的EBS服务 <br> python客户端：[python-cinderclient](https://github.com/openstack/python-cinderclient) |
| [diskimage-builder](https://github.com/openstack/diskimage-builder) | 为openstack(虚拟机或者物理机）提供磁盘镜像，文件系统镜像和Ramdisk镜像打包的工具 |
| [gantt](https://github.com/openstack/gantt) | openstack各部件的通用调度器框架，目前大部分的代码来自于nova-scheduler <br> python客户端：[python-ganttclient](https://github.com/openstack/python-ganttclient) |
| [glance](https://github.com/openstack/glance) | 为openstack提供虚拟机镜像的发现，注册，管理和传递服务 <br> python客户端：[python-glanceclient](https://github.com/openstack/python-glanceclient)|
| [heat](https://github.com/openstack/heat) | Heat是openstack中应用编配服务，可以用于管理基于openstack应用的整个生命周期，其对用于AWS的CloudFormation服务, 并且可以直接使用用于CloudFormation的启动模版 <br> python客户端：[python-heatclient](https://github.com/openstack/python-heatclient) |
| [heat-cfntools](https://github.com/openstack/heat-cfntools) | Heat服务的helper组件，运行于虚拟机内部，用于自动部署应用，向平台通知事件等 |
| [heat-templates](https://github.com/openstack/heat-templates) | Heat中自动部署应用的参考模版集合 |
| [ironic](https://github.com/openstack/ironic) | ironic将物理机器像虚拟机一样进行管理，例如使用PXE boot和ipmi管理各种硬件，并且使用插件方式来支持各种设备相关的硬件 <br> python客户端：[python-ironicclient](https://github.com/openstack/python-ironicclient) |
| [keystone](https://github.com/openstack/keystone) | openstack的身份认证服务，负责身份验证、服务规则和服务令牌的功能 <br> python客户端：[python-keystoneclient](https://github.com/openstack/python-keystoneclient) |
| [os-apply-config](https://github.com/openstack/os-apply-config) | 将openstack中cloud metadata信息(如heat中的template)转换成虚拟机OS可以识别的配置文件的工具 |
| [os-collect-config](https://github.com/openstack/os-collect-config) | openstack实例中收集平台中配置文件的工具 |
| [os-refresh-config](https://github.com/openstack/os-refresh-config) | openstack实例的工具，用于监控heat模版的变化，并在必要时重启实例中的应用和服务 |
| [oslo-incubator](https://github.com/openstack/oslo-incubator) | oslo被设计为openstack各个服务的公共基础代码，因此其他服务(如nova，neutron服务)可重用的代码则需要加入到oslo中 <br> oslo解析命令行参数和.ini配置文件的API：[oslo.config](https://github.com/openstack/oslo.config) |
| [savanna](https://github.com/openstack/savanna) | 用于在openstack上快速建立Hadoop集群的服务，对应AWS的EMR <br> python客户端：[python-savannaclient](https://github.com/openstack/python-savannaclient) <br> horizon插件：[savanna-dashboard](https://github.com/openstack/savanna-dashboard) <br> 集成Hadoop的OS打包工具：[savanna-image-elements](https://github.com/openstack/savanna-image-elements) <br> savanna其他部件：[savanna-extra](https://github.com/openstack/savanna-extra) | 
| [trove](https://github.com/openstack/trove) | trove是openstack的弹性数据库服务，目标是支持mysql, Cassandra, redis等多种类型，对应于AWS的RDS服务 <br> python客户端：[python-troveclient](https://github.com/openstack/python-troveclient) |
| [python-openstackclient](https://github.com/openstack/python-openstackclient) | 对其他各个python-*client模块进行封装，旨在为openstack各服务提供统一的命令行调用和API接口 |
| [tuskar](https://github.com/openstack/tuskar) | 管理数据中心中openstack各个服务安装和部署的组件，同时，它还为平台管理者提供了诸如性能监控，健康度统计，使用量统计和硬件采购决策等功能。<br> python客户端：[python-tuskarclient](https://github.com/openstack/python-tuskarclient) <br> horizon插件：[tuskar-ui](https://github.com/openstack/tuskar-ui) |
| [tempest](https://github.com/openstack/tempest) | openstack的集成测试工具，被设计成能够在任意规模的云环境中运行 |
| [TripleO-incubator](https://github.com/tripleo-incubator) | TripleO(三个O，openstack-on-openstack)是个有趣的项目，通过在openstack中部署openstack开发测试环境，从功能代码更新到部署到实际生产环境自动化完成，并且具有速度快，代码可靠特点和持续集成/持续交付的能力 <br> 构建用于TripleO部署的镜像的打包工具：[tripleo-image-elements](https://github.com/openstack/tripleo-image-elements) <br> TripleO的heat部署模版：[tripleo-heat-templates](https://github.com/openstack/tripleo-heat-templates)


## [openstack-dev主页](https://github.com/openstack-dev) 

| 项目名称 | 描述 |
|:---:|:---:|
| [devstack](https://github.com/openstack-dev/devstack) | devstack是一组自动化安装和部署openstack各个子项目的工具脚本， 使用简单的配置即可实现部署单节点和多节点等多种模式 |
| [pbr](https://github.com/openstack-dev/pbr) | pbr是python build reasonableness的简称，它是一个简化openstack子项目build过程的工具。开发者通过编写setup.cfg文件，即可实现项目的自动化构建，从这个意义上讲，它和java的ant工具类似 |
| [hacking](https://github.com/openstack-dev/hacking) | hacking是openstack开发者的python代码规范测试工具 |
| [grenade](https://github.com/openstack-dev/grenade) | 通常我们使用devstack来安装openstack，但是如果我们需要在此基础上升级每个项目，那么需要使用grenade |
| [cookiecutter](https://github.com/openstack-dev/cookiecutter) | openstack每个子项目的基础代码模版 |
| [openstack-nose](https://github.com/openstack-dev/openstack-nose) | openstack的一个nosetests插件 |
