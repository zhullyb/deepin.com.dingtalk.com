# deepin.com.dingtalk.com（一份非官方的钉钉容器）

* 当前版本6.0.0.11902

* 更新时间:2021/06/22

* 注意事项

    1. 针对Arch系，我已经打包至AUR，仓库名为```deepin.com.dingtalk.com```

    2. 默认自带了deepin-wine5-stable，不需要额外安装依赖

    5. 任何发行版遇到中文字体显示错误都可以尝试安装中文字体解决，这里推荐```fonts-wqy-microhei```

    6. 本deb包现仅支持deepin/uos，其他deb系发行版安装后需自行调整图标和desktop文件的路径（仓库里我已经给出相应文件），或者直接在终端使用`/opt/apps/deepin.com.dingtalk.com/files/run.sh`命令启动。
    
* 更新日志
    * 2021/06/22
        - 删除Updater以禁用热更新
        - 更新到 6.0.0.11902 版本
        - 采用的是统信的打包脚本`deepin-wine-tools-0608.zip`
    * 2020/09/30
        * 修复输入框无法显示文字的bug [[3]](https://github.com/zhullyb/deepin.com.dingtalk.com/issues/3)
    
* ISSUE和PR
    * 如果出现了问题或者有什么好的建议，欢迎提出ISSUE，我会及时进行处理
    * 如果有自己的想法且已经实现了，欢迎与我联系（本仓库自始至终不承担开源功能，毕竟几百兆的二进制文件拆开来放到gtihub也没什么意义）

* 依赖：

    ```
    libasound2 (>= 1.0.16), libc6 (>= 2.28), libglib2.0-0 (>= 2.12.0), libgphoto2-6 (>= 2.5.10), libgphoto2-port12 (>= 2.5.10), libgstreamer-plugins-base1.0-0 (>= 1.0.0), libgstreamer1.0-0 (>= 1.4.0), liblcms2-2 (>= 2.2+git20110628), libldap-2.4-2 (>= 2.4.7), libmpg123-0 (>= 1.13.7), libopenal1 (>= 1.14), libpcap0.8 (>= 0.9.8), libpulse0 (>= 0.99.1), libudev1 (>= 183), libvkd3d1 (>= 1.0), libx11-6, libxext6, libxml2 (>= 2.9.0), ocl-icd-libopencl1 | libopencl1, udis86, zlib1g (>= 1:1.1.4), libasound2-plugins, libncurses6 | libncurses5 | libncurses, deepin-wine-plugin-virtual
    ```

* 感谢名单
    * [钉钉官方](https://www.dingtalk.com/)
    * [统信UOS](https://www.chinauos.com/)
    * [wszqkzqk](https://github.com/wszqkzqk/deepin-wine-ubuntu)
    * [gorquan](https://github.com/gorquan)
    
* 最后
    * 该包不涉及任何反编译行为，希望能让更多Linux用户能够用上钉钉客户端，希望官方能够早日研发出Linux平台的钉钉
    * 该包仅限于提供给各位学习使用，请勿用于商业行为！
    * 如果引用包时请带上Github仓库链接，请不要直接占用成果，谢谢合作！
    * 采用 6.0.0.11902 版本是我从 [wine游戏助手](https://winegame.net/games/dingtalk/) 中获得的灵感，钉钉的最新版本出现了标题栏按钮消失的问题，目前暂时无解决方案[[11]](https://github.com/zhullyb/deepin.com.dingtalk.com/issues/11)，故采用的6.0.0.11902 规避此bug。
