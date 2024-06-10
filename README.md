#一级标题
##二
###三
####四
#####五
\<br\>
*yiduan*

**yidun**

***yiduan***

~~yiduan~~
## \-\-\-   分割线

\>yinyong
>一级
>>
>>>
>>>>四级
>你是最聪明的
>>你真帅
>>>啊啊啊啊
>>>>aaaaaa
##无序\*
* 二次元
  * 原神
* 大逃杀
  * csgo
##有序 1.
1. 物理
   1. 原子
   2. 量子
2. 高数
   1. 线性代数
1. 嘿嘿
   * 无敌
    2. 天才
名称|技能|排行
--|:--:|--:
蝙蝠侠|有钱|36
闪电侠|快|21
蜘蛛侠|帅|1

###代码片段

```c
#inclde<stdio>
int main()
{

}

```
```cpp
#include<iostream>
```
```python

```
```bash

关键字查询:
xx(python) awesome:查该标签下的xx
(Python)项目
xx(python) tutorial:查询xx(python)资料、书
籍、文档
xx(socket)
sample:查询对应技术(socket)的
代码样本
GitHub三要素:
Repository 仓库
仓库是github项目管理存储基本单位
一个仓库中存储一个项目，一个用户可以拥有多个仓
库，一般仓库分为public，private
Commit 提交:
程序员在整个开发周期，有大量的对代码资源的选代
和修改，都可以通过commit的方式进行记录,便于程
序员回溯代码, 即使这些代码被删除
提交便于使用者观察整个工程的开发流程以及设计流
程
Branch 分支:
在仓库中可以包含多个分支，分支才是代码文件的第
一存储单位，默认的仓库主分支为master/main
*不仅可以管理代码存储，便于多人协作开发
pwd
ps aux


仓库内容
Code，资源存储，
代码资源，
二进制，项目管理脚
本，许可证等等
issues，使用时遇到的bug 或 进行提交，等待反馈
README，使用markdown语言编写，工程自述文
件，开发进度，，版本更新，使用介绍等等
LICENSE 许可证:GPL2.0,3.0.Apahce 2.0，Mit，这
些许可证，给使用者最大使用权限以及最少的限制
Git软件，分布式版本控制系统
仓库管理软件，使用git管理私人代码或企业代码
 git init // 创建本地仓库
*后续对仓库的操
作，都要在仓库位置(master)
修改或添加config配置项
git config -list //查看git的配置文件
修改或添加config配置项
git config --global user.name
//用户名
7/注册邮
箱
生成本机设备密文
ssh-keygen -t rsa -C“注册邮箱’
# 创建本地
密文 *去对应的目录下查找密文文件
rsa.pub 复制密文，粘贴到 settings -> ssH key and
GPG -> new ssh key ->粘贴
测试关联是否完成
ssh -T git@github.com
ssh远程登录
2、为目标仓库起别名，定位目标仓库，后
续上传
git remote add orgin(别名)SSH地址(云端仓库
地址)
git remote remove origin
#删除地址别名
git add code.c
#添加内容
#将缓冲区数据提交到本地仓库
OIM
git commit -m
git commit -m
"备注信息!
#生成提交记录
git push origin(云端仓库地址)master
#将
本地仓库内容推到云端仓库
git status
git rm code.c
#查看状态
#删除本地文件及仓库中文件
git restore code.c
#复位误删除文件(仓库存
在)
代码更新的依赖关系被破坏
本地内容要比云端新,完成更新替换， 但是如果直接
修改云端内容,导致,本地内容无法再次提交
先拉取 git pul 云端内容 与本地内容合井或操作,
而后再次推即可
git pull --rebase origin master
```
git rebase --abort
My repository (master
#忽略新版，此时还不能上
传
git rebase --skip
#需略旧版，更新本地后可
以上传
git rebase --continue #版本合并，解决冲突后可
以直接上
下载开源代码
git clone "https仓库地址
#下载开源项目code
资源
分支Branch
关于分支的相关命令，
创建分支、选择分支、合并分
支等等
Markdown语言
Markdown，文本修饰语言，
用特殊符号修饰正文效
果
标题修饰符
修饰符与正文之间要有空格
正文内容
换行使用/</br/ >标签
段落缩进(行首加两个空格，即是分段)也可以换行
\转义字符
字体效果
#段测试文本，斜体
##一段测试文本，粗体


###
~~
