# Git 使用
把这个看了 https://liaoxuefeng.com/books/git/introduction/index.html
# 进入项目目录
cd your-project-folder

# 初始化 Git 仓库
git init

# 关联远程仓库（如 GitHub/GitLab）
git remote add origin 远程仓库地址
# 示例：
git remote add origin https://github.com/username/repo.git
                      https://github.com/EzraXen/C.git
usernam 用户名。repo 仓库名

创建一个新的仓库时需要配置  也可以在https://github.com/new 配置


# 提交修改流程

## 查看修改状态
- git status 查看当前修改状态 	显示哪些文件被修改/新增/删除（红色未跟踪，绿色已暂存）。

## 将文件添加到暂存区
### 添加单个文件
git add 文件名

### 添加所有修改/新增文件
git add .

### 添加所有修改（不包括新增文件）
git add -u


## 提交到本地仓库
git commit -m "描述你的修改内容"
规范一点  git commit -m "feat-冒泡排序"

