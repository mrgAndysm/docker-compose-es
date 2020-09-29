es6.8.0 集群配置
===========================

###########环境依赖
官方镜像已被迁移至 阿里云 registry镜像
es：版本6.8.0
###########部署步骤
1.在目录下直接 docker-compose up


###########目录结构描述
├── Readme.md                   // help
├── head                         // elasticsearch-head
├── node                      // es节点信息
│   ├── es1	 // 主节点信息
│        └── data      
│        └── elasticsearch.yml 
│   ├── es2               // 从节点信息
│        └── data
│        └── elasticsearch.yml
└── docker-compose.yml


###########可横向扩容