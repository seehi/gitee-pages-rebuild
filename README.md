普通版码云Pages，git push后需要到界面上手动rebuild，网页才会生效，此项目调用码云的rebuild接口进行自动化

# 配置环境变量
```
export GITEE_USERNAME=
export GITEE_PASSWORD=
export GITEE_REPO=
```
# Python依赖
```
不低于python3.6

pip install -i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com -r requirements.txt
```

# 运行
```
python rebuild.py
成功会显示: rebuild result: true
```

# 感谢
```
https://github.com/yanglbme/gitee-pages-action

此项目参照上面项目
此项目的优势在于配置简单，不会有垃圾邮件，结合shell脚步就可以一键自动化
```