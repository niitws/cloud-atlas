.. _openstack_env_hardware:

==================
OpenStack硬件环境
==================

OpenStack硬件环境要求(最小的验证功能环境和一些CirrOS实例):

- 管控节点： 1处理器，4GB内存，5GB存储
- 计算节点:  1处理器，2GB内存，10GB存储

随着OpenStack服务数量增加以及虚拟机实例增加，硬件要求则提升以便保证性能。

所有OpenStack节点需要安装64位奥做系统，并采用最小化安装。虽然单一磁盘分区可以满足基本安装要求，但是建议采用LVM作为节点存储。

.. note::

   由于硬件需求和OpenStack规模和用途强烈相关，所以后续我再逐步补充实践经验。
