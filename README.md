# k8s
#kubeadm部署k8s的基本教程，已跑通

https://www.cnblogs.com/Leo_wl/p/8511902.html

#安装dashboard，注意浏览器访问要加https://才行

https://cloud.tencent.com/developer/article/1380902


https://packages.cloud.google.com/apt/doc/apt-key.gpg下载不了的情况，添加/etc/apt/sources.list.d/kubernetes.list如下内容

deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted

deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted

deb http://mirrors.aliyun.com/ubuntu/ xenial universe

deb http://mirrors.aliyun.com/ubuntu/ xenial-updates universe

deb http://mirrors.aliyun.com/ubuntu/ xenial multiverse

deb http://mirrors.aliyun.com/ubuntu/ xenial-updates multiverse

deb http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse

deb https://mirrors.aliyun.com/kubernetes/apt kubernetes-xenial main
