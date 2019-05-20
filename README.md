# OpenStack课程大纲

1. OpenStack简介
   OpenStack起源，解决了什么问题和痛点，企业实际应用场景，现状，和容器生态世界的竞争与协作；

2. OpenStack项目介绍
   OpenStack全景概览，社区组织，运作方式，核心项目，文档；

3. OpenStack基础
   OpenStack项目入门基础技术，OpenStack社区架构设计，基础依赖；

4. 认证服务
   Keystone服务关键概念详解，部署模式，部署操作；

5. 镜像服务
Glance的作用和概念，镜像格式，qcow2 raw rbd等格式介绍，部署操作；

6. 计算服务
Qemu技术讲解和操作；
KVM虚拟化技术讲解和操作；
Libvirt技术讲解和操作；
Nova架构设计和服务组件分析；
Nova部署；
nova核心概念如cell， 调度 ，资源更新，硬件管理，创建删除流程讲解，以novaclient输出为讲解指南；

7. 网络服务
 网络基础技术namespace dhcp vxlan gre ovs openflow等技术讲解；
 Neutron网络项目架构和服务组件讲解；
 neutron项目部署和操作；
 neutron数据流量走向图；

8. 存储服务
存储技术基础，块存储、对象存储、文件存储；
Cinder项目设计架构和服务组件讲解；
Ceph服务讲解；
cinder和ceph服务部署并对接；

9. horizon服务
horizon服务讲解，部署；

10. OpenStack集群性能
rabbitmqq mysql nova neutron网络节点 存储等服务的性能；

11. OpenStack HA
 控制、计算、存储、网络、基础服务等各大组件的HA；

12. OpenStack集群规划和运维
集群节点硬件要求，软件版本，组网，增删节点；

13. OpenStack演示和错误排查
 虚拟机创建删除resize迁移等重要操作
 创建删除代码流程分析
 错误排查
 源码修改和调试

14. 容器生态圈
容器世界的技术；
容器生态圈发展变迁演进；
容器领域解决的问题，场景，需求，如何蚕食OpenStack份额；
Kubernetes服务讲解；
OpenStack和容器生态如何共存；

## 基础知识
1.linux基础，cgroup namespace等；
2.cpu内存虚拟化，kvm qemu libvirt；
3.网络基础，vlan vxlan gre ovs openflow net-namespace；
4.存储基础，raid lvm qcow ceph；
5.容器docker k8s相关；



