# MiniX Notes

## Push code to github

1. Add files

   ```shell
   git add .
   ```

2. Commit

   ```shell
   git commit -m "comment"
   ```

3. Push

   ```shell
   git push origin master
   ```

## 在github粗略统计自己提交的代码次数以及行数

1. 选择一个Public的Repositories，选择Insights，再选择Contributors：

   ![Contributors](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/Contributors.png)

   再来一个局部的放大图：

   ![Contributor时Details](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/ContributorsDetails.png)

   这是一个新建的Repositories，数据比较难看。

## Add “Include” folder to VC project

1. 工程目录结构

   ![工程目录结构](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/工程目录结构.png)

2. 设置头文件目录

   在Microsoft Visual C++中依次打开Project-->Settings（或者按快捷键Alt+F7）:

   ![project_settings](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/project_settings.png)

   选择C/C++选项卡，把Category更改为Preprocessor，然后在Additional include directories中添加自定义的头文件目录。
