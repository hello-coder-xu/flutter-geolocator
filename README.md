此项目fork flutter_geolocator  v13.0.2版本

目的是为了解决firebase 上的崩溃问题 ：https://591.to/7kMs

相对flutter_geolocator  v13.0.2的改动查看 [PR](https://591.to/7kM9)

这个PR很早就有了，与现在代码间隔太久，里面其他代码已经过时，因此重新fork官方版本修改





# Flutter geolocator plugin

The Flutter geolocator plugin is built following the federated plugin architecture. A detailed explanation of the federated plugin concept can be found in the [Flutter documentation](https://flutter.dev/docs/development/packages-and-plugins/developing-packages#federated-plugins). This means the geolocator plugin is separated into the following packages:

1. [`geolocator`][1]: the app facing package. This is the package users depend on to use the plugin in their project. For details on how to use the [`geolocator`][1] plugin you can refer to its [README.md][2] file.
2. [`geolocator_android`][3]: this package contains the endorsed Android implementation of the geolocator_platform_interface and adds Android support to the [`geolocator`][1] app facing package. More information can be found in its [README.md][4] file;
3. [`geolocator_apple`][5]: this package contains the endorsed iOS and macOS implementations of the geolocator_platform_interface and adds iOS and macOS support to the [`geolocator`][1] app facing package. More information can be found in its [README.md][6] file;
4. [`geolocator_web`][7]: this package contains the endorsed web implementation of the geolocator_platform_interface and adds web support to the [`geolocator`][1] app facing package. More information can be found in its [README.md][8] file;
5. [`geolocator_windows`][9]: this package contains the endorsed Windows implementation of the geolocator_platform_interface and adds Windows support to the [`geolocator`][1] app facing package. More information can be found in its [README.md][10] file;
6. [`geolocator_platform_interface`][11]: this package declares the interface which all platform packages must implement to support the app-facing package. Instructions on how to implement a platform package can be found in the [README.md][12] of the [`geolocator_platform_interface`][11] package.

[1]: ./geolocator
[2]: ./geolocator/README.md
[3]: ./geolocator_android
[4]: ./geolocator_android/README.md
[5]: ./geolocator_apple
[6]: ./geolocator_apple/README.md
[7]: ./geolocator_web
[8]: ./geolocator_web/README.md
[9]: ./geolocator_windows
[10]: ./geolocator_windows/README.md
[11]: ./geolocator_platform_interface
[12]: ./geolocator_platform_interface/README.md
