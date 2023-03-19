# git生成ssh密钥
ssh-keygen -t rsa -C "jiahui_shu@163.com"
一直回车就可以生成密钥

# github保存密钥
cat ~/.ssh/id_rsa.pub
复制查看的内容，添加到 settings--->ssh 保存即可
