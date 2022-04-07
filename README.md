# k8s-flink-cluster

Distributed Flink cluster deployed on k8s (via kubespray), running on GCP (can be run on any cloud provider).

Details will follow, check `cluster.txt` for details for now. Uses `flink:1.7.2` Docker image because the newer ones don't come out with native HDFS support (maybe a future TODO?).

### TODO's

- Provide GCP provisioning
- Provide kubespray provisioning steps
- Provide more up to date docker image with up to date flink, hadoop with HDFS support (optional).

Author: Batuhan Mert Varilci
