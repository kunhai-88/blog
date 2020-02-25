
1. 设置Jenkins默认密码。
```shell
sudo passwd jenkins
```
2. 切换到 jenkins用户 
```
su jenkins
```
3. 创建ssh秘钥，并将公钥内容 id_rsa.pub 拷贝到目标服务器 /root/.ssh/authorized_keys 文件内。
4. 执行一次scp命令拷贝文件到目标服务器。