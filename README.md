# githubip
国内访问github太慢，可以通过修改host的方法加快速度

> 注意：目前通过修改host加速github的效果，个人之间存在差异，有的加了之后可能没效果。
1. 如果是想要快速克隆项目，可以借用gitee当跳板。先用gitee导入github的项目，然后从gitee中clone项目。项目clone下来后，修改.git/config中的url，改成git中对应的url。
2. 如果是要下载release包，可以借助其他人搭好服务。例如[https://d.serctl.com/](https://d.serctl.com/)

# 使用方法

1.克隆项目到本地，在本地运行 `getip.py` (注意：如果你使用的是python3，则需要安装BeautifulSoup4,不然会报错)
2.根据得到的ip修改host
