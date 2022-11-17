# Shell

1. zsh
2. cd tmp/ && mkdir missing
3. man touch
4. cd missing && touch semester
5. vim semester && ...
6. 文件没有执行的权限
7. sh 有执行权限 ./semester 没有权限
8. man chmod
9. chmod -x semester
10. stat semester | grep Modify > last-modified.txt
11. 用的是虚拟机，好像没有办法查看这些信息
