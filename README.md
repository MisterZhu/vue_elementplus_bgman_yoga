一个通用的后台管理系统，涉及功能看api（支持增删改查，图片视频上传删除七牛云等）

VUE_APP_BASE_API = https://aimissu.top/api/
#VUE_APP_BASE_API = https://106.52.86.134:8080/api/

VUE_APP_QINIU_URL = https://qiniu.aimissu.top/

# 用户管理

# 登录接口
VUE_APP_USER_LOGIN = /user/login
# 注册接口
VUE_APP_USER_REGISTER = /user/register
# 用户信息
VUE_APP_USER_INFO = /user/info
# 退出登录
VUE_APP_USER_LOGOUT = /user/logout

# 七牛云api

# 获取七牛token接口
VUE_APP_QINIU_TOKEN = /qiniu/token
# 七牛云删除文件
VUE_APP_QINIU_REMOVE_FILE = /qiniu/remove_file

# 分类接口

# 分类新增
VUE_APP_CATE_ADD = /category/add
# 分类查询
VUE_APP_CATE_GET = /category/get
# 分类编辑
VUE_APP_CATE_EDIT = /category/edit
# 分类删除
VUE_APP_CATE_DET = /category/det
# 分类详情
VUE_APP_CATE_DETAIL = /category/detail

# 文章接口

# 文章新增
VUE_APP_ARTICLE_ADD = /article/add
# 文章查询
VUE_APP_ARTICLE_GET = /article/get
# 文章编辑
VUE_APP_ARTICLE_EDIT = /article/edit
# 文章删除
VUE_APP_ARTICLE_DET = /article/det
# 分类下所有的文章
VUE_APP_ARTICLE_CATELIST = /article/catelist
# 所有文章
VUE_APP_ARTICLE_ARTLIST = /article/artlist

# project-name

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
