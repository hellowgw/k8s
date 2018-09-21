# 目录结构
```[root@controller ~]# tree k8s/
k8s/
├── calico
│   ├── conf
│   │   └── calicoctl.cfg
│   └── yaml
│       ├── base-config.yaml
│       ├── bgp-calico.yaml
│       ├── calico.yaml
│       └── rbac.yaml
├── etcd
│   ├── conf
│   │   └── etcd.conf
│   └── system
│       └── etcd.service
├── kubernetes
│   ├── system
│   │   ├── kube-apiserver.service
│   │   ├── kube-controller-manager.service
│   │   ├── kubelet.service
│   │   ├── kube-proxy.service
│   │   └── kube-scheduler.service
│   └── yaml
└── ssl
    ├── admin-csr.json
    ├── ca-csr.json
    ├── etcd-csr.json
    ├── kube-proxy-csr.json
    └── kubernetes-csr.json
```

