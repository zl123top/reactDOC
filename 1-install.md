# 安装
## 安装淘宝镜像
    $ npm install -g cnpm --registry=https://registry.npm.taobao.org
    修改下载资源
    $ npm config set registry https://registry.npm.taobao.org
    安装某个模块
    $ cnpm install [name]

## 入门的时候，用配置好的一套脚手架
    $ cnpm install -g create-react-app
    $ create-react-app my-app
    $ cd my-app/
    $ npm start

## push
    $ git init                                  # 初始化
    $ git add README.md                         # 添加文件
    $ git commit -m "添加 README.md 文件"        # 提交并备注信息
    $ git remote add origin git@github.com:childdd/reactDOC.git # 连接远程仓库
    $ git push -u origin master # 第一次推送

## 当远程已经有了项目文件，先clone后push
    $ git clone git@github.com:childdd/reactDOC.git # 克隆

## 修改后推送
    $ git push origin master    # 推送到 Github

## 补充
    git bush 按中键粘贴，选中自动复制。在选项中设置。