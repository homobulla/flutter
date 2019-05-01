## flutter

### flutter 安装说明

比起`rn`的安装过程简直是简易，需要注意的是运行`flutter doctor`检测结果是
把`vscode`和`android studi`的缺失环境同时展出，只需要安装一个对应的`IDE`即可。

唯一需要注意的是，要将 `flutter` 依赖的安装源换成国内镜像:

```bash
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
```

### 依赖

即第三方包，在`pubspec.yaml`文件中写入依赖模块：

```dart
dependencies:
    flutter:
        sdk: flutter

    # The following adds the Cupertino Icons font to your application.
    # Use with the CupertinoIcons class for iOS style icons.
    cupertino_icons: ^0.1.2
    english_words: ^3.1.0 # 这里是一些依赖，类似于package.json
```
