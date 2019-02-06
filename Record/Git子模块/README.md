# 子模块-将其它仓库放在某仓库子目录下
以将经典文本分类项目[cnn-text-classification-tf](https://github.com/dennybritz/cnn-text-classification-tf "With a Title")克隆到我[github](https://github.com/dennybritz/cnn-text-classification-tf "With a Title")中[Algorithm](https://github.com/Roggu123/Algorithm "With a Title")仓库子目录下为例。子目录具体路径为[Algorithm/Practice/NLP/cnn-text-classification-tf](https://github.com/Roggu123/Algorithm/tree/master/Practice/NLP "With a Title")。
## 步骤
1.外部仓库克隆到本地子目录中；

	localhost:NLP ruogulu$ git submodule add https://github.com/dennybritz/cnn-text-classification-tf.git cnn-text-classification-tf
	Cloning into '/Users/ruogulu/Desktop/Study/Algorithm/Practice/NLP/cnn-text-classification-tf'...
	remote: Enumerating objects: 234, done.
	remote: Total 234 (delta 0), reused 0 (delta 0), pack-reused 234
	Receiving objects: 100% (234/234), 1.11 MiB | 7.00 KiB/s, done.
	Resolving deltas: 100% (121/121), done. 
	
2.加入子模块后立刻运行 <font color=#FF0000>git status</font> ，查看文件变动；

	localhost:NLP ruogulu$ git status
	On branch master
	Your branch is up to date with 'origin/master'.

	Changes to be committed:  
		(use "git reset HEAD <file>..." to unstage)

	modified:   ../../.gitmodules
	new file:   cnn-text-classification-tf

3.文件 <font color=#FF0000>.gitmodules</font> 是一个配置文件，保存了项目 URL 和你拉取到的本地子目录
	
	localhost:NLP ruogulu$ cat ../../.gitmodules
	[submodule "Practice/NLP/NLP"]
	path = Practice/NLP/NLP
	url = https://github.com/dennybritz/cnn-text-classification-tf.git
	[submodule "Practice/NLP/cnn-text-classification-tf"]
	path = Practice/NLP/cnn-text-classification-tf
	url = https://github.com/dennybritz/cnn-text-classification-tf.git

4.执行上传至远程库的操作，细节见 ../Record/4

	localhost:NLP ruogulu$ git commit -am 'Added cnn-text-classification-tf module'
	[master 1f68457] Added cnn-text-classification-tf module  
		35 files changed, 22 insertions(+), 2368 deletions(-)
		rewrite Book/README.md (84%)
	delete mode 100644 Practice/CV/FaceDetection/face_detection_comparision/face_detection_comparision.xcodeproj/project.pbxproj
	delete mode 100644 Practice/CV/FaceDetection/face_detection_comparision/face_detection_comparision.xcodeproj/project.xcworkspace/contents.xcworkspacedata
	.....  此处省略若干delete mode
	create mode 160000 Practice/NLP/cnn-text-classification-tf
	localhost:NLP ruogulu$ git push -u origin master
	Enter passphrase for key '/Users/ruogulu/.ssh/id_rsa': 
	Counting objects: 25, done.
	Delta compression using up to 4 threads.
	Compressing objects: 100% (23/23), done.
	Writing objects: 100% (25/25), 12.37 KiB | 1.77 MiB/s, done.
	Total 25 (delta 8), reused 0 (delta 0)
	remote: Resolving deltas: 100% (8/8), completed with 7 local objects.
	To github.com:Roggu123/Algorithm.git
	13558c6..1f68457  master -> master
	Branch 'master' set up to track remote branch 'master' from 'origin'.

## 推送本地改动注意细节
<br>见图片4

