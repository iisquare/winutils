# winutils

winutils.exe hadoop.dll and hdfs.dll binaries for hadoop on windows

## refer

- [cdarlint/winutils](https://github.com/cdarlint/winutils)
- [steveloughran/winutils](https://github.com/steveloughran/winutils)
- [Native windows libraries for hadoop](https://github.com/notepass/hadoop-native-win-libs)


## how to use

place a copy of hadoop-ver folder on your local drive
set environment vars:
```
HADOOP_HOME=<your local hadoop-ver folder>
PATH=%PATH%;%HADOOP_HOME%\bin
```
then you'll pass the "no native library" and "access0" error
