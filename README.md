# cp_dockercompose

docker-compose的组件集合,提供了常见场景下的调试用`docker-compose`模板

## 提供的模板

| 模板名                      | 说明                                                 |
| --------------------------- | ---------------------------------------------------- |
| `kafka_broker_standalone`   | 单机模式以kafka作为中间人的生产消费模式的compose文件 |
| `etcd_broker_standalone`    | 单机模式以etcd作为中间人的发布订阅模式的compose文件  |
| `server_standalone`         | 单机模式的服务的compose文件                          |
| `universal_task_standalone` | 单机模式的通用任务程序的compose文件                  |