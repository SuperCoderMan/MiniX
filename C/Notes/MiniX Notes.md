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

## Add “Include” folder to VC project

1. 工程目录结构

   ![工程目录结构](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/工程目录结构.png)

2. 设置头文件目录

   在Microsoft Visual C++中依次打开Project-->Settings（或者按快捷键Alt+F7）:

   ![project_settings](https://github.com/SuperCoderMan/MiniX/blob/master/C/Images/project_settings.png)

   选择C/C++选项卡，把Category更改为Preprocessor，然后在Additional include directories中添加自定义的头文件目录。
