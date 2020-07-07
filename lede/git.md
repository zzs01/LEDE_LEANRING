* Git放弃本地所有修改，强制更新

1. git fetch --all

2. git reset --hard origin/master

3. 放弃修改：git clean -df
--------------------------
* 报错：Invalid revision range

  * 在仓库中搜错误信息后边的字符串，然后将之修改为自己commit的任意一个版本号
