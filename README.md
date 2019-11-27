# Zookeeperize 
```bash
python
from modules.utils.zookeeper import zk_power
z = zk_power(zookeeper_hosts=['192.168.100.10'])
z.zk.start()
z.set('/tmp', 'test')
print(z.get('/tmp'))
...
```
