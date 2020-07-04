# photo
这个文档是用于markdown显示文件
##1. 将图片存到github  
###1.1 点击仓库名photo，点击new file  
这里直接新建一个txt文件，初始为photo/，新建photo/tensoeflow_learn/yiyi.txt，这样会自动新建一个文件夹
###1.2 上传图片  
新建好文件夹便会有一个add file，点开下拉菜单会有upload，拖拽上来就可以了。
#2. 复制图片下载链接  
#3. 在Markdown文档中调用
```
![Aaron Swartz](图片网址)
```
#4. 删除文件以及本地上传照片
这个就比较麻烦了，需要本地新建文件夹，在文件夹上点击git bush here，运行
```
git clone https://github.com/bupt-bricklayer/photo.git
```
clone好之后进入photo文件夹进行操作，操作完之后右击文件夹，commit，提交后再次git bush
```
git push #将修改添加到远端
```
