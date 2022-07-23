# linux_aliases

#### 介绍
DIY Linux shell 命令，方便运维

# 如何使用? 
复制三个文件（docker_alias_diy,kubectl_aliases_diy,linux_aliases_diy）到 /root/目录下

然后

vi /root/.bashrc


```
source /root/docker_alias_diy
source /root/kubectl_aliases_diy
source /root/linux_aliases_diy
```


保存退出

root用户执行命令

`source /root/.bashrc`