# Jupyter Notebook 安装 PHP 内核

## docker 部署
构建和运行
```shell
docker build -t php-jupyter:v1 .

docker run -d --name php-jupyter -p 8888:8888 php-jupyter:v1
```

## 详见

https://www.cuiwei.net/p/1391718888