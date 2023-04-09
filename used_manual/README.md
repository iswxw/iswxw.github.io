### 使用手册

#### Hexo 使用

常用命令

```bash
npm install hexo-cli -g                                        // 安装hexo
hexo init iswxw                                                // 初始化博客目录： 
cd iswxw                                                       // 初始化完成后，我们就进入我们的目录
npm install                                                    // 安装 依赖包
hexo clean                                                     // 清除缓存文件 (db.json) 和已生成的静态文件 (public)
hexo g                                                         // 生成静态页面 
hexo s                                                         // 把你的网站本地运行起来
hexo d                                                         // 发布服务到指定的服务器
```

#### 项目维护

##### 项目预览

```bash
# 1. 请求历史文件
hexo clean

# 2. 生成静态页面
hexo g

# 3. 发布本地服务
hexo s
```

##### 项目发布

```bash
# 1. 请求历史文件
hexo clean

# 2. 生成静态页面
hexo g

# 3. 发布 到码云 https://gitee.com/iswxw/iswxw.git
hexo d 

# 4. push 到指定仓库
git push git@github.com:iswxw/iswxw.github.io.git main
```
