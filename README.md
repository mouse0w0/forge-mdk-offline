# forge-mdk-offline

### 加速站点
- [加速站点1](https://tool.mintimate.cn/gh/)
- [加速站点2](https://ghproxy.com/)
- [加速站点3](https://github.91chi.fun/)
- [加速站点4](https://github.abskoop.workers.dev/)

### 使用说明[1.12.2-14.23.5.2847以上版本]：
1. 下载后打开压缩包，将会看到两个文件夹，分别为`.gradle`和`forge-x.x.x-x.x.x.xxxx-xxx`。
2. 将`.gradle`文件夹解压至`C:\Users\<当前用户>`（例如`C:\Users\administrator`）文件夹下，如果该目录已存在该文件夹，则覆盖。
3. 将`forge-x.x.x-x.x.x.xxxx-xxx`文件夹解压至任意全英文（路径名称不得有中文等非ASCII字符）路径下。
4. 按照所使用的 IDE`在 forge-x.x.x-x.x.x.xxxx-xxx 文件夹下打开命令提示符，运行指令：
    1. IntelliJ IDEA：`gradlew genIntelliJRuns`
    2. Eclipse：`gradlew eclipse genEclipseRuns`
    3. VSCode：`gradlew genVSCodeRuns`
3. 直接在IDE中以**Gradle项目**打开或导入`forge-x.x.x-x.x.x.xxxx-xxx`文件夹。
6. 按照相关Forge教程进行后续操作即可。

### 使用说明[1.12.2-14.23.5.2847及以下版本]：
1. 下载后打开压缩包，将会看到两个文件夹，分别为`.gradle`和`forge-x.x.x-x.x.x.xxxx-xxx`。
2. 将`.gradle`文件夹解压至`C:\Users\<当前用户>`（例如`C:\Users\administrator`）文件夹下，如果该目录已存在该文件夹，则覆盖。
3. 将`forge-x.x.x-x.x.x.xxxx-xxx`文件夹解压至任意全英文（路径名称不得有中文等非ASCII字符）路径下。
4. 在解压后的`forge-x.x.x-x.x.x.xxxx-xxx`文件夹下打开cmd（命令提示符），运行指令：`gradlew setupDecompWorkspace`。
5. 按照相关Forge教程进行后续操作即可。