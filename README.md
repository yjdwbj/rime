* Rime 是一个跨平台的输入框架。它的核心（或者说「后端」）是 librime 引擎，不同平台的前端实现共用这个后端。目前在 GitHub RIME 组织中维护的前端实现有三个：

    用于 Windows 的 Weasel 「小狼毫」；
    用于 macOS 的 Squirrel 「鼠须管」；
    用于 Linux 的 ibus-rime 「中州韵」——Rime 本身的中文名字也叫「中州韵输入法引擎」。

* 同步之后可以看到文件夹下的相关配置，基本上和桌面版的 RIME 是一致的：

    default.yaml，各输入方案共享的全局配置
    default.custom.yaml，（可选）对 default.yaml 的修改，不会随着客户端的更新而被覆盖，所以对 default 的修改可以通过 patch 的方式放入该配置文件
    xxx.schema.yaml，xxx 输入方案的配置
    xxx.custom.yaml，（可选）对 xxx.schema.yaml 的自定义修改
    xxx.dict.yaml, xxx 输入方案的词库（字典）


* 这里主要是记录网上链接，各种配置与词库都是热心网友供献，你可以稍作修改，或者不作修改都能有很好的体验。如果自已有空也可以定制出自已的风格，且可以
  同步各种平台上使用。


* [Android 上的 RIME 输入法 trime 同文输入法使用 ](https://einverne.github.io/post/2021/04/use-trime-input-method-rime-on-android.html)
* [使用 Trime 在 Android 上输入五笔](https://wzyboy.im/post/1251.html)
* [同文安卓輸入法平臺/Trime: Rime IME for Android](https://github.com/osfans/trime)
* [RIME | 中州韻輸入法引擎](https://rime.im/)
* [Rime 定製指南](https://github.com/rime/home/wiki/CustomizationGuide)

