# usslab-ddls-generate

Inspired by [ccf-deadlines](https://github.com/ccfddl/ccf-deadlines).

## Best Practice

### 配置环境

- node.js 版本号一定要16 在[官网](https://nodejs.org/)下载安装

- 检查node以及npm版本

   ```
   node -v
   ```

   ```
   npm -v
   ```

- 安装vue

   ```
   npm install -g @vue/cli
   ```

### 修改

修改src文件夹下面的vue文件就可以修改前端界面

### 编译运行

```
npm run build
```

如果没有错误则

```
npm run serve
```

在本地查看页面

### 部署到github

运行scripts下面的generate_allconf.py生成allconf.yml

在dist里面创建conference，文件夹下只有allconf.yml和types.yml

将dist文件夹复制到一个新的github仓库，部署到github page即可



