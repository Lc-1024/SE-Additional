# Usage of Git

### Git的大概介绍

1. 个人的GitHub整体类似于一棵树，Lc-1024是根节点，而各个Repositories是叶节点，每个Repository都代表一个项目/目录/仓库，每次新开一个项目/文件夹都需要new Repository，然后再在该目录下进行更改。
2. Git是一种类似于SVN的工具（或者是SVN类似于Git才对），由Linux之父开发，可以成为分布式版本控制系统，它可以在本地或者云端都有数据备份，同样的也可以追溯到历史版本，GitHub相当于是提供了一个云端地服务器，而SVN只能更新到云端/从云端下载，受网络局限很大。
3. Git可以连接到个人的GitHub（或者Gitee等）上，用于开源和备份。
4. Git从官网下载，完全下一步地安装，可以右键打开，需要配置name和email，并且创建SSH与GitHub账号连接，之后便可以用Git进行下载和更新。Git Bash可以类似于Linux下的Terminal来管理文件。

### Git的具体使用

1. git clone [url] 从网址下载Repository，并且在当前路径下创建该文件夹，之后可以在这个文件夹中创建/修改文件并上传；
2. 也可以将下载过来的文件夹中的所有文件（包括隐藏文件夹）全部移到本地已有的对应文件夹中，之后便可以直接对已有的文件夹进行上传。
3. git add . 可以将文件添加到本地的缓冲区中，也可以一个个写文件名，选择性上传，通过git status观察缓冲区中有哪些文件，然后使用git commit保存到本地的仓库中，还可以用git push上传到云端。![git](D:\SE-Additional\hw\hw_1\git.jpg)
4. 对于fetch/pull/checkout还不是很了解。