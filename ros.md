

# ros命令

roslaunch prototype:
```shell
$ roslaunch package_name file.launch
$ roslaunch <package-name> <launch-filename> [args]  ## roslaunch会找到存在于指定的package中的launch文件并且启动这个launch文件
```

rosrun prototype:
```shell
$ rosrun [package_name] [node_name]  ## rosrun可以不用知道package路径，而通过package_name直接启动它里面的node

```
