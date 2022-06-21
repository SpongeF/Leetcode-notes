# 常用操作

### 提交代码

1. git pull
2. git status
3. git add .
   1. git diff A.py
   2. git add A.py
   3. git diff B.py
   4. git add B.py
      ...
4. git commit -m '注释'
5. git push

### 切换分支

1. git checkout -b wh/branch_a
2. 进行文件修改
3. git add .
4. git commit -m '注释'
5. git push
6. git checkout master (切换回主分支)

### merge 代码

1. git checkout master (将 wh/branch_a 分支的内容 merge 到 master 中，先把自己切换回 master 分支)
2. git merge wh/branch_a (直接使用 merge 命令进行合并，即可将 wh/branch_a 的代码同步过来)
3. git push
