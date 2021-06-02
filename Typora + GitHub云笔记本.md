## Typora + GitHub云笔记本
### 1、前提准备
	Typora + GitHub安装
### 2、创建GitHub项目
	z
### 3、在本地创建同名文件夹

####  1）如下图找到路径，然后检查文件的状态，再激活文件夹，使其产生一个git类型的文件夹

![image-20210602191006662](D:\Software\笔记\Typora\note\picture\image-20210602191006662.png)

![image-20210602191130397](D:\Software\笔记\Typora\note\picture\image-20210602191130397-1622632721725.png)

### 4、将本地文件与GitHub项目关联


![image-20210602191506154](D:\Software\笔记\Typora\note\picture\image-20210602191506154.png)
### 5、上传文件到GitHub
#### 1）如果文件夹为空，创建文件才可以上传
#### 2）文件夹不为空，
* 	执行git status检查文件夹状态
* 	git add .注意，这里的空格+句号
* 	git commit -m "develop_note"链接GitHub文件
* 	git push origin master执行上传操作

#### 3）遇到问题

![image-20210602193503545](D:\Software\笔记\Typora\note\picture\image-20210602193503545.png)

解决方案：

![image-20210602193551981](D:\Software\笔记\Typora\note\picture\image-20210602193551981.png)

### 6、大功告成
	以后有新的笔记，直接右键Git Bash Here>>>输入git push origin master就可以实时上传笔记了
创建脚注就是这样[^RUNOOB]。
[^RUNOOB] ：[^业精于勤，荒于嬉；行成于思，毁于随]

