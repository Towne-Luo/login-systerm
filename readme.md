## 说明

这是一个基于Django的登录和注册app，参考[刘江老师](<https://www.liujiangblog.com/course/django/102>)教程完成，上传以作分享查用。

## 使用方法

1. git clone https://github.com/luotong11/login-systerm.git
2. 修改setting.example.py为setting.py
3. pip 安装依赖
4. 创建数据库和数据表

```python
python manage.py makemigrations
python manage.py migrate
```

5. 运行服务器

```
python manage.py runserver
```

