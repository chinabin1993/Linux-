# Linux-常用命令
Linux常用命令，以后继续添加
### Liunx常见命令

1. [显示日期](#日期指令-date)
2. [显示日历](#日历指令-cal)
3. [计算器](#计算器指令-bc)
4. [关机指令](#关机指令-shutdown)
5. [重要热键](#几个重要的热键指令)
6. [数据同步](#数据同步写入磁盘--sync)
8. [显示当前目录](#显示当前目录-pwd)
9. [创建新目录](#mkdir)
10. [创建文件](#touch)


### 日期指令-date
```dash
date
```
### 日历指令-cal
```dash
cal
```
### 计算器指令-bc

```dash
bc
```
**需要注意：bc只能计算整数，如果需要计算小数，需要设置`scale=number`**

### 几个重要的热键指令
* **Tab** 「档案补全」功能
* **当前程序停掉**
*  **键盘输入结束**

### 数据同步写入磁盘--sync
输入sync，那些在内存中尚未被更新的数据，就会被写入硬盘中；
```dash
sync
```
### 关机指令-shutdown
```dash
shutdown -h now
```
### 显示当前目录-pwd
```dash
pwd
```
### mkdir
```dash
mkdir xxx
```
### touch
```dash
touch xxx
```
