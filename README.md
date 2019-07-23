# 调整访问地址
修改`values.yaml`中的ingress.hosts地址

# 安装
`helm install --name demo .`

# 卸载
`helm delete --purge demo`

# 访问
`curl http://[ingress.hosts]`