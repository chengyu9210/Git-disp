git config --global user.name "Your Name"  配置用户名

git config --global user.email "mail@example.com" 配置邮箱

git config --global credential store 保存配置

// 以上代码只需要在自己的电脑上任意位置执行一次



git init 										在当前目录创建仓库

git clone https//：12312313213  				克隆一个远程仓库

git add .                                       把当前目录所有**文件**和**文件夹内所有文件**都添加到暂存区

git add *.txt                                   把当前目录所有**txt文件**和**文件夹内所有txt文件**都添加到暂存区



git commit -m"在这里添加提交备注"

// 如果不-m，则会自动打开vim进行备注的编辑，没有备注则会报错，提交失败



git log

git log --oneline  				查看提交信息





git reset                撤销commit，分3个模式

git reset --soft, git reset --hard, git reset --mixed 默认情况是mixed

区别：soft模式 工作区、暂存区都不清空。hard 工作区 暂存区都清空。mixed 工作区不清空，暂存区清空