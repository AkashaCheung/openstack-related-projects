# openstack社区项目介绍

## [openstack主页](https://github.com/openstack)

| 项目名称 | 描述 |
|:---:|:---:|
| [nova](https://github.com/openstack/nova) | openstack中的计算组织控制器，支持多种虚拟化技术(如KVM，LXC等)，对应于AWS的EC2服务 |
| [swift](https://github.com/openstack/swift) | openstack中的非结构化、弹性可伸缩、高可用的分布式对象存储服务，对应于AWS的S3服务 |
| [horizon](https://github.com/openstack/horizon) | 基于Django实现，是openstack各个服务的web操作和查看面板，并且结构可扩展，很方便添加新的服务界面 |
| [neutron](https://github.com/openstack/horizon) | openstack的网络组织控制器，提供云计算环境下的虚拟网络功能 |
| [marconi](https://github.com/openstack/marconi) | openstack的消息队列服务，对应于AWS的SNS和SQS |
| [ceilometer](https://github.com/openstack/ceilometer) | openstack中的事件收集服务，为监控和计费提供支持，这些事件包括平台中用户的资源使用情况和资源的健康状态 |
| [cinder](https://github.com/openstack/cinder) | 为openstack平台提供volume卷管理和虚拟块设备服务，对应于AWS的EBS服务 |
| [diskimage-builder](https://github.com/openstack/diskimage-builder) | 为openstack(虚拟机或者物理机）提供磁盘镜像，文件系统镜像和Ramdisk镜像打包的工具 |
| [gantt](https://github.com/openstack/gantt) | openstack各部件的通用调度器框架，目前大部分的代码来自于nova-scheduler
|
| [glance](https://github.com/openstack/glance) | 为openstack提供虚拟机镜像的发现，注册，管理和传递服务 |
| [heat](https://github.com/openstack/heat) | Heat是openstack中应用编配服务，可以用于管理基于openstack应用的整个生命周期，其对用于AWS的CloudFormation服务, 并且可以直接使用用于CloudFormation的启动模版 |
| [heat-cfntools](https://github.com/openstack/heat-cfntools) | Heat服务的helper组件，运行于虚拟机内部，用于自动部署应用，向平台通知事件等 |
| [heat-templates](https://github.com/openstack/heat-templates) | Heat中自动部署应用的参考模版集合 |
| [ironic](https://github.com/openstack/ironic) | ironic将物理机器像虚拟机一样进行管理，例如使用PXE boot和ipmi管理各种硬件，并且使用插件方式来支持各种设备相关的硬件
| [keystone](https://github.com/openstack/keystone) | openstack的身份认证服务，负责身份验证、服务规则和服务令牌的功能 |
| [os-apply-config](https://github.com/openstack/os-apply-config) | 将openstack中cloud metadata信息(如heat中的template)转换成虚拟机OS可以识别的配置文件的工具 |
| [os-collect-config](https://github.com/openstack/os-collect-config) | openstack实例中收集平台中配置文件的工具 |
| [os-refresh-config](https://github.com/openstack/os-refresh-config) | openstack实例的工具，用于监控heat模版的变化，并在必要时重启实例中的应用和服务 |
