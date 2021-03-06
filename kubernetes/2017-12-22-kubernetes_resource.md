
---
layout:     post
title:      "kubernetes 学习资源汇总"
subtitle:   "kubernetes 学习资源汇总"
date:       2017-12-22
author:     "yucs"
catalog:    true
categories: 
	- Kubernetes

tags:
    - Kubernetes
     
---

- **资讯：** [weekly.dockone.io](http://weekly.dockone.io/index)

- **gitbook:[Kubernetes指南](https://github.com/feiskyer/kubernetes-handbook)**（系统全面）
- **gitbook: [kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook)**(偏向实践)

- **微课堂：** [IBM开源技术微讲堂 kuberntes系列](https://www.ibm.com/developerworks/community/wikis/home?lang=en#!/wiki/W30b0c771924e_49d2_b3b7_88a2a2bc2e43/page/IBM%E5%BC%80%E6%BA%90%E6%8A%80%E6%9C%AF%E5%BE%AE%E8%AE%B2%E5%A0%82)

- 官方开发相关参考：[community:design-proposals](https://github.com/kubernetes/community/tree/master/contributors/design-proposals) && [community:devel](https://github.com/kubernetes/community/tree/master/contributors/devel)

-  技术博客
    - [我的kubernets整理学习系列](https://yucs.github.io/categories/Kubernetes/)
	- [cizixs](http://cizixs.com/) 
	- [https://jimmysong.io](https://jimmysong.io/)
 



- docker :[Docker从入门到实践](https://github.com/yeasy/docker_practice)
-  容器网络:[SDN网络指南](https://github.com/feiskyer/sdn-handbook)


--------

# 实践生态

[请注意，容器技术圈已迈入后Kubernetes时代](https://mp.weixin.qq.com/s/0gwRcMdORZcor5rP4Fr7Jw)(好)


[Kubernetes的工业级实践](https://mp.weixin.qq.com/s/vyUi1V4pmYQr5_9T2Qqygg)


[干货视频 | Kubernetes在vivo容器云平台中的实践](https://mp.weixin.qq.com/s/nNUaL1noCryWm3sVFsy6CQ)


<!--[我的kubernets整理学习系列](https://yucs.github.io/categories/Kubernetes/)各文章包含的链接就不在这重复列出
-->

# 部署 
- [利用Ansible部署kubernetes集群](https://github.com/gjmzj/kubeasz)： 官方kubeadm下载的镜像需要翻墙，国内网络环境下使用[AllInOne](https://github.com/gjmzj/kubeasz/blob/master/docs/quickStart.md)部署更方便，单机多主机部署都支持。

 - 基于二进制方式部署和利用ansible-playbook实现自动化：既提供一键安装脚本，也可以分步执行安装各个组件，同时讲解每一步主要参数配置和注意事项。
 
  - 二进制方式部署优势：有助于理解系统各组件的交互原理和熟悉组件启动参数，有助于快速排查解决实际问题


<!---
- [Kubernetes指南 之 kubeadm工作原理](https://github.com/feiskyer/kubernetes-handbook/blob/master/components/kubeadm.md)
 
[kubeadm工作机制分析](http://blog.csdn.net/waltonwang/article/details/70162993)
- [源码分析之kubeadm](http://blog.csdn.net/u010278923/article/details/70225173)--> 
 
# controller
- [kube-controller-manager 分析](https://ggaaooppeenngg.github.io/zh-CN/2017/11/27/kube-controller-%E5%88%86%E6%9E%90/)

<!--- node conroller
   
  - [Kubernetes Node Controller源码分析之配置篇](http://blog.csdn.net/waltonwang/article/details/75269847)

  - [Kubernetes Node Controller源码分析之执行篇]()

  - [Kubernetes Node Controller源码分析之创建篇](http://blog.csdn.net/waltonwang/article/details/76359220)

  - [Kubernetes Node Controller源码分析之Taint Controller](http://blog.csdn.net/waltonwang/article/details/76474386)
-->

<!--![pod_create](/picture/pod_create.png)
--> 


# event
- [Kubernetes(K8s)Events介绍（上）](https://www.kubernetes.org.cn/1031.html)
- [Kubernetes Events介绍（中）](https://www.kubernetes.org.cn/1090.html)
- [Kubernetes Events介绍（下）](https://www.kubernetes.org.cn/1195.html)
- [kubelet 源码分析： 事件处理](http://cizixs.com/2017/06/22/kubelet-source-code-analysis-part4-event)
 


# schedule 
- [Kubernetes调度详解](http://dockone.io/article/2885)
- [Kubernetes Scheduler是如何工作的](http://dockone.io/article/2625)
- [kubernetes 调度器指北](https://ggaaooppeenngg.github.io/zh-CN/2017/09/26/kubernetes-%E6%8C%87%E5%8C%97/)


# API 
- [Kubernetes API 分析 ( Kube-apiserver )](https://www.kubernetes.org.cn/3119.html)

- [api-conventions](https://github.com/kubernetes/community/blob/master/contributors/devel/api-conventions.md)

- [Kubernetes deep dive: API Server – part 1](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-1/)
- [Kubernetes deep dive: API Server – part 2](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-2/)
- [ubernetes deep dive: API Server – part 3](https://blog.openshift.com/kubernetes-deep-dive-api-server-part-3a/)


<!--
 最新1.8 重构过，代码差异比较大：[Kubernetes1.5源码分析(一) apiServer启动分析](http://dockone.io/article/2159)
[apiserver的list-watch代码解读](https://www.kubernetes.org.cn/174.html)-->





 
 