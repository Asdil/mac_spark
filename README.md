# mac_spark
作为笔记几下mac如何安装spark
<br>1.首先需要安装brew

<br>2.安装java8，由于现在jdk已经是jdk9了所以需要指定安装jdk8
<br>brew tap caskroom/versions
<br>brew cask install java8
<br>查看java是否安装好，版本 1.8.0_152

<br>3.安装scala和sbt
<br>brew install scala
<br>brew install sbt
<br>查看scala是否安装好，版本2.12.4

<br>4.安装spark
<br>brew install apache-spark
<br>打开终端查看
<br>cd /usr/local/Cellar/apache-spark/2.2.0/bin/  ./spark-shell

<br>5.设置pycharm
<br>下载重github下载 spark.py 文件  和word.txt
<br>run->Edit Configuretions->Environment variables 添加
<br>PYTHONPATH /usr/local/Cellar/apache-spark/2.2.0/libexec/python
<br>SPARK_HOME /usr/local/Cellar/apache-spark/2.2.0/libexec

<br>运行文件里spark.py程序
