# Helm Chart - Kafka with Kraft(without zookeeper)
## 注意事项
## Notice
此chart主要功能是快速部署单节点Kraft版Kafka(不使用zookeeper的情况下)，适用于个人和测试用，*不适用于生产环境*。
This helm chart setup Kafka fast without zookeeper(kraft) in SINGLE NODE, mainly for personal usage or test, is *not suitable for production*

## 食用说明
## Usage
```
#1
git clone https://github.com/littleplus/helm-chart-kafka-with-kraft.git

#2
## 修改value.yaml文件
## Modify value.yaml

#3
helm upgrade helm-chart-kafka-with-kraft --install -n kafka --create-namespace helm-chart-kafka-with-kraft
```