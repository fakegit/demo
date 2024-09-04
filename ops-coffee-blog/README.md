# 项目说明

此项目为ops-coffee.cn网站生成工具，依赖环境

- python 3.6
- django 2.2
- adminlte 2.4

# 部署方法
1. 安装基础环境
```
pip install -r requirements.txt
```

2. 初始化数据库
```
python manage.py makemigrations ops_coffee
python manage.py migrate
```

创建用户
```
python manage.py createsuperuser
```

3. 运行项目
```
python manage.py runserver 0.0.0.0:80
```

4. 浏览器访问

![欢迎关注微信公众号【运维咖啡吧】](/images/qrcode.jpg)

5. 对应文章

配合对应文章看源码更有效，文章地址：[直达链接，点我查看](https://blog.ops-coffee.cn/s/7g2wncQG1lIziOmtBxXwEw)