
# canal-go

[![Build Status](https://travis-ci.org/withlin/canal-go.svg?branch=master)](https://travis-ci.org/withlin/canal-go)
[![Go Report Card](https://goreportcard.com/badge/github.com/withlin/canal-go)](https://goreportcard.com/badge/github.com/withlin/canal-go)

感谢阿里云canal团队

#### 本项目使用docker 搭建mysl+canal-sesrver+canal-admin+es+kibana
实现mysql数据同步到es

#### 注意mysql对应到表结构 先到es创建对应到索引 mapping

#### 注意 canal-server下到配置文件 canal_local.properties  和canal.properties 的值
canal.admin.passwd = 6BB4837EB74329105EE4568DDA7DC67ED2CA2AD9 是密码的password("你的密码")
可以在mysql里面 使用 select password("你的密码");查看密码 这里的密码是123456的加密结果，实际改成你们自己设置的
