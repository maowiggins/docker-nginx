# docker-nginx
**本容器集成了GEOIP模块，可以实现基于地区进行页面等限制**
## 快速启动

1、docker run启动

**强烈建议添加 `--privileged` 参数来启用，因为本容器在启动时会有几个内核参数的修改的动作。**

```bash
$ docker run -d --name redis --privileged -p 6379:6379 wiggins/nginx:latest
```

2、通过docker-compose来实现快速启动
```bash
$ curl -LkO https://github.com/maowiggins/docker-nginx/raw/master/docker-compose.yml
$ docker-compose up -d
```
