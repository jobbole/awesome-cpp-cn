# C++ 资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-cpp](https://github.com/fffaraz/awesome-cpp) 就是 fffaraz 发起维护的 C++ 资源列表，内容包括：标准库、Web应用框架、人工智能、数据库、图片处理、机器学习、日志、代码分析等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-cpp 资源列表，我们将对各个资源项进行编译整理。
- 整理后的内容，将收录在[伯乐在线资源频道](http://www.importnew.com/)。可参考已整理的内容：
  - 《[libPhenom：Facebook开源的高性能 C 语言并发编程框架](http://www.importnew.com/libphenom/)》
  - 《[OpenFrameworks：一个用C++编码的跨平台开源工具包](http://www.importnew.com/openframeworks/)》

* * *

### 目录
* [标准库](#标准库)
* [框架](#框架)
* [人工智能](#人工智能)
* [异步事件循环](#异步事件循环)
* [音频](#音频)
* [生态学](#生态学)
* [压缩](#压缩)
* [并发性](#并发性)
* [容器](#容器)
* [密码学](#密码学)
* [数据库](#数据库)
* [调试](#调试)
* [游戏引擎](#游戏引擎)
* [图形用户界面](#图形用户界面)
* [图形](#图形)
* [图像处理](#图像处理)
* [国际化](#国际化)
* [Json](#Json)
* [日志](#日志)
* [机器学习](#机器学习)
* [数学](#数学)
* [多媒体](#多媒体)
* [网络](#网络)
* [物理学](#物理学)
* [机器人学](#机器人学)
* [科学计算](#科学计算)
* [脚本](#脚本)
* [序列化](#序列化)
* [视频](#视频)
* [虚拟机](#虚拟机)
* [Web应用框架](#Web应用框架)
* [XML](#XML)
* [多项混杂](#多项混杂)
* [软件](#软件)
* [编译器](#编译器)
* [在线编译器](#在线编译器)
* [调试器](#调试器)
* [集成开发环境（IDE）](#集成开发环境（IDE）)
* [构建系统](#构建系统)
* [静态代码分析](#静态代码分析)

* * *

### 如何参与本项目？

<!-- 从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 有 C++ 开发经验；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「C++大全」
 -->

* * *

### 本项目的参与者

- 维护者：[tangyouhua](https://github.com/tangyouhua)

- 贡献者：[JingerJoe](http://www.jobbole.com/members/JingerJoe/)、[云中游](http://www.jobbole.com/members/tonyaaron/)、[冰斌](http://www.jobbole.com/members/libing1209/)、[Juliesand](http://www.jobbole.com/members/Juliesh/)、[ZZMarquis](https://github.com/ZZMarquis)、[颜闽辉](https://github.com/yanminhui/)、You

注：名单不分排名，不定期补充更新

* * *

<!-- ### 奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

* 整理超过 20 个资源后，可在伯乐在线上开通打赏；
* 每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
* [奖励详情](http://hao.jobbole.com/rewards/)

* * *
 -->

### 标准库

C++标准库，包括了STL容器，算法和函数等。

*   C++ Standard Library：是一系列类和函数的集合，使用核心语言编写，也是C++ISO自身标准的一部分。[官网](http://en.wikipedia.org/wiki/C%2B%2B_Standard_Library)
*   Standard Template Library：标准模板库。[官网](http://en.wikipedia.org/wiki/Standard_Template_Library)
*   C POSIX library：POSIX系统的C标准库规范。[官网](http://en.wikipedia.org/wiki/C_POSIX_library)
*   ISO C++ Standards Committee：C++标准委员会。[官网](https://github.com/cplusplus)

### 框架

C++通用框架和库

*   Apache C++ Standard Library：是一系列算法，容器，迭代器和其他基本组件的集合。[官网](http://stdcxx.apache.org/)
*   ASL：Adobe源代码库提供了同行的评审和可移植的C++源代码库。[官网](http://stlab.adobe.com/)
*   Boost：大量通用C++库的集合。[官网](https://github.com/boostorg)
*   BDE：来自于彭博资讯实验室的开发环境。[官网](https://github.com/bloomberg/bde)
*   Cinder：提供专业品质创造性编码的开源开发社区。[官网](http://libcinder.org/)
*   Cxxomfort：轻量级的，只包含头文件的库，将C++ 11的一些新特性移植到C++03中。[官网](http://ryan.gulix.cl/fossil.cgi/cxxomfort/)
*   Dlib：使用契约式编程和现代C++科技设计的通用的跨平台的C++库。[官网](http://dlib.net/)
*   EASTL：EA-STL公共部分。[官网](https://github.com/paulhodge/EASTL)
*   ffead-cpp：企业应用程序开发框架。[官网](https://github.com/sumeetchhetri/ffead-cpp)
*   Folly：由Facebook开发和使用的开源C++库。[官网](https://github.com/facebook/folly)
*   JUCE：包罗万象的C++类库，用于开发跨平台软件。[官网](https://github.com/julianstorer/JUCE)
*   [libPhenom](http://hao.jobbole.com/libphenom/)：用于构建高性能和高度可扩展性系统的事件框架。[官网](https://github.com/facebook/libphenom)、[GitHub](https://github.com/facebook/libphenom)
*   LibSourcey：用于实时的视频流和高性能网络应用程序的C++11 evented IO。[官网](https://github.com/sourcey/libsourcey)
*   LibU：C语言写的多平台工具库。[官网](https://github.com/koanlogic/libu)
*   Loki：C++库的设计，包括常见的设计模式和习语的实现。[官网](http://loki-lib.sourceforge.net/)
*   MiLi：只含头文件的小型C++库。[官网](https://code.google.com/p/mili/)
*   [openFrameworks](http://hao.jobbole.com/openframeworks/)：开发C++工具包，用于创意性编码。[官网](http://www.openframeworks.cc/)
*   Qt：跨平台的应用程序和用户界面框架。[官网](http://qt-project.org/)
*   Reason：跨平台的框架，使开发者能够更容易地使用Java，.Net和Python，同时也满足了他们对C++性能和优势的需求。[官网](http://code.google.com/p/reason/)
*   ROOT：具备所有功能的一系列面向对象的框架，能够非常高效地处理和分析大量的数据，为欧洲原子能研究机构所用。[官网](http://root.cern.ch/)
*   STLport：是STL具有代表性的版本。[官网](http://www.stlport.org/)
*   STXXL：用于额外的大型数据集的标准模板库。[官网](http://stxxl.sourceforge.net/)
*   Ultimate++：C++跨平台快速应用程序开发框架。[官网](http://www.ultimatepp.org/)
*   Windows Template Library：用于开发Windows应用程序和UI组件的C++库。[官网](http://sourceforge.net/projects/wtl/)
*   Yomm11：C++11的开放multi-methods。[官网](https://github.com/jll63/yomm11)

### 人工智能

*   btsk：游戏行为树启动器工具。[官网](https://github.com/aigamedev/btsk)
*   Evolving Objects：基于模板的，ANSI C++演化计算库，能够帮助你非常快速地编写出自己的随机优化算法。[官网](http://eodev.sourceforge.net/)
*   Neu：C++11框架，编程语言集，用于创建人工智能应用程序的多用途软件系统。[官网](https://github.com/JackieXie168/neu)

### 异步事件循环

*   Boost.Asio：用于网络和底层I/O编程的跨平台的C++库。[官网](http://think-async.com/)
*   libev：功能齐全，高性能的时间循环，轻微地仿效libevent，但是不再像libevent一样有局限性，也修复了它的一些bug。[官网](http://libev.schmorp.de/)
*   libevent：事件通知库。[官网](http://libevent.org/)
*   libuv：跨平台异步I/O。[官网](https://github.com/libuv/libuv)

### 音频

音频，声音，音乐，数字化音乐库

*   FMOD：易于使用的跨平台的音频引擎和音频内容的游戏创作工具。[官网](http://www.fmod.org/)
*   Maximilian：C++音频和音乐数字信号处理库。[官网](https://github.com/micknoise/Maximilian)
*   OpenAL：开源音频库---跨平台的音频API。[官网](http://www.openal.org/)
*   Opus：一个完全开放的，免版税的，高度通用的音频编解码器。[官网](http://opus-codec.org/)
*   Speex：免费编解码器，为Opus所废弃。[官网](http://www.speex.org/)
*   Tonic：C++易用和高效的音频合成。[官网](https://github.com/TonicAudio/Tonic)
*   Vorbis：Ogg Vorbis是一种完全开放的，非专有的，免版税的通用压缩音频格式。[官网](http://xiph.org/vorbis/)

### 生态学

生物信息，基因组学和生物技术

*   libsequence：用于表示和分析群体遗传学数据的C++库。[官网](http://molpopgen.github.io/libsequence/)
*   SeqAn：专注于生物数据序列分析的算法和数据结构。[官网](http://www.seqan.de/)
*   Vcflib：用于解析和处理VCF文件的C++库。[官网](https://github.com/ekg/vcflib)
*   Wham：直接把联想测试应用到BAM文件的基因结构变异。[官网](https://github.com/jewmanchue/wham)

### 压缩

压缩和归档库

*   bzip2：一个完全免费，免费专利和高质量的数据压缩。[官网](http://www.bzip.org/)
*   doboz：能够快速解压缩的压缩库。[官网](https://bitbucket.org/attila_afra/doboz/overview)
*   PhysicsFS：对各种归档提供抽象访问的库，主要用于视频游戏，设计灵感部分来自于Quake3的文件子系统。[官网](https://icculus.org/physfs/)
*   KArchive：用于创建，读写和操作文件档案（例如zip和 tar）的库，它通过QIODevice的一系列子类，使用gzip格式，提供了透明的压缩和解压缩的数据。[官网](https://projects.kde.org/projects/frameworks/karchive)
*   LZ4：非常快速的压缩算法。[官网](https://code.google.com/p/lz4/)
*   LZHAM：无损压缩数据库，压缩比率跟LZMA接近，但是解压缩速度却要快得多。[官网](https://code.google.com/p/lzham/)
*   LZMA：7z格式默认和通用的压缩方法。[官网](http://www.7-zip.org/sdk.html)
*   LZMAT：及其快速的实时无损数据压缩库。[官网](http://www.matcode.com/lzmat.htm)
*   miniz：单一的C源文件，紧缩/膨胀压缩库，使用zlib兼容API，ZIP归档读写，PNG写方式。[官网](https://code.google.com/p/miniz/)
*   Minizip：Zlib最新bug修复，支持PKWARE磁盘跨越，AES加密和IO缓冲。[官网](https://github.com/nmoinvaz/minizip)
*   Snappy：快速压缩和解压缩。[官网](https://code.google.com/p/snappy/)
*   ZLib：非常紧凑的数据流压缩库。[官网](http://zlib.net/)
*   ZZIPlib：提供ZIP归档的读权限。[官网](http://zziplib.sourceforge.net/)

### 并发性

并发执行和多线程

*   Boost.Compute：用于OpenCL的C++GPU计算库。[官网](https://github.com/kylelutz/compute)
*   Bolt：针对GPU进行优化的C++模板库。[官网](https://github.com/HSA-Libraries/Bolt)
*   C++React：用于C++11的反应性编程库。[官网](https://github.com/schlangster/cpp.react)
*   Intel TBB：Intel线程构件块。[官网](https://www.threadingbuildingblocks.org/)
*   Libclsph：基于OpenCL的GPU加速SPH流体仿真库。[官网](https://github.com/libclsph/libclsph)
*   OpenCL：并行编程的异构系统的开放标准。[官网](https://www.khronos.org/opencl/)
*   OpenMP：OpenMP API。[官网](http://openmp.org/)
*   Thrust：类似于C++标准模板库的并行算法库。[官网](http://thrust.github.io/)
*   HPX：用于任何规模的并行和分布式应用程序的通用C++运行时系统。[官网](https://github.com/STEllAR-GROUP/hpx/)
*   VexCL：用于OpenCL/CUDA 的C++向量表达式模板库。[官网](https://github.com/ddemidov/vexcl)

### 容器

*   C++ B-tree：基于B树数据结构，实现命令内存容器的模板库。[官网](https://code.google.com/p/cpp-btree/)
*   Hashmaps：C++中开放寻址哈希表算法的实现。[官网](https://github.com/goossaert/hashmap)

### 密码学

*   Bcrypt：一个跨平台的文件加密工具，加密文件可以移植到所有可支持的操作系统和处理器中。[官网](http://bcrypt.sourceforge.net/)
*   BeeCrypt：。[官网](https://github.com/fffaraz/awesome-cpp/blob/master)
*   Botan：C++加密库。[官网](http://botan.randombit.net/)
*   Crypto++：一个有关加密方案的免费的C++库。[官网](http://www.cryptopp.com/)
*   GnuPG：OpenPGP标准的完整实现。[官网](https://www.gnupg.org/)
*   GnuTLS：实现了SSL，TLS和DTLS协议的安全通信库。[官网](http://www.gnutls.org/)
*   Libgcrypt：[官网](http://www.gnu.org/software/libgcrypt/)
*   libmcrypt：[官网](https://github.com/fffaraz/awesome-cpp/blob/master)
*   LibreSSL：免费的SSL/TLS协议，属于2014 OpenSSL的一个分支。[官网](http://www.libressl.org/)
*   LibTomCrypt：一个非常全面的，模块化的，可移植的加密工具。[官网](https://github.com/libtom/libtomcrypt)
*   libsodium：基于NaCI的加密库，固执己见，容易使用。[官网](https://github.com/jedisct1/libsodium)
*   Nettle：底层的加密库。[官网](http://www.lysator.liu.se/~nisse/nettle/)
*   OpenSSL：一个强大的，商用的，功能齐全的，开放源代码的加密库。[官网](http://www.openssl.org/)
*   Tiny AES128 in C：用C实现的一个小巧，可移植的实现了AES128ESB的加密算法。[官网](https://github.com/kokke/tiny-AES128-C)
*   GmSSL：支持国密SM2/SM3/SM4算法的OpenSSL分支。[官网](https://github.com/guanzhi/GmSSL)

### 数据库

数据库，SQL服务器，ODBC驱动程序和工具

*   hiberlite：用于Sqlite3的C++对象关系映射。[官网](https://github.com/paulftw/hiberlite)
*   Hiredis：用于Redis数据库的很简单的C客户端库。[官网](https://github.com/redis/hiredis)
*   LevelDB：快速键值存储库。[官网](https://github.com/google/leveldb)
*   LMDB：符合数据库四大基本元素的嵌入键值存储。[官网](http://symas.com/mdb/)
*   MySQL++：封装了MySql的C API的C++ 包装器。[官网](http://www.tangentsoft.net/mysql++/)
*   RocksDB：来自Facebook的嵌入键值的快速存储。[官网](https://github.com/facebook/rocksdb)
*   SQLite：一个完全嵌入式的，功能齐全的关系数据库，只有几百KB，可以正确包含到你的项目中。[官网](http://www.sqlite.org/)

### 调试

调试库， 内存和资源泄露检测，单元测试

*   Boost.Test：Boost测试库。[官网](http://www.boost.org/doc/libs/master/libs/test/doc/html/index.html)
*   Catch：一个很时尚的，C++原生的框架，只包含头文件，用于单元测试，测试驱动开发和行为驱动开发。[官网](https://github.com/philsquared/Catch)
*   CppUnit：由JUnit移植过来的C++测试框架。[官网](http://www.freedesktop.org/wiki/Software/cppunit/)
*   CTest：CMake测试驱动程序。[官网](http://www.cmake.org/cmake/help/v2.8.8/ctest.html)
*   googletest：谷歌C++测试框架。[官网](http://code.google.com/p/googletest/)
*   ig-debugheap：用于跟踪内存错误的多平台调试堆。[官网](https://github.com/deplinenoise/ig-debugheap)
*   libtap：用C语言编写测试。[官网](https://github.com/zorgnax/libtap)
*   MemTrack：—用于C++跟踪内存分配。[官网](http://www.almostinfinite.com/memtrack.html)
*   microprofile：跨平台的网络试图分析器。[官网](https://bitbucket.org/jonasmeyer/microprofile/overview)
*   minUnit：使用C写的迷你单元测试框架，只使用了两个宏。[官网](http://www.jera.com/techinfo/jtns/jtn002.html)
*   Remotery：用于web视图的单一C文件分析器。[官网](https://github.com/Celtoys/Remotery)
*   UnitTest++：轻量级的C++单元测试框架。[官网](http://unittest-cpp.sourceforge.net/)

### 游戏引擎

*   Cocos2d-x：一个跨平台框架，用于构建2D游戏，互动图书，演示和其他图形应用程序。[官网](http://www.cocos2d-x.org/)
*   Grit：社区项目，用于构建一个免费的游戏引擎，实现开放的世界3D游戏。[官网](http://gritengine.com/)
*   Irrlicht：C++语言编写的开源高性能的实时#D引擎。[官网](http://irrlicht.sourceforge.net/)
*   Polycode：C++实现的用于创建游戏的开源框架（与Lua绑定）。[官网](http://polycode.org/)

### 图形用户界面

*   CEGUI：很灵活的跨平台GUI库。[官网](http://cegui.org.uk/)
*   FLTK：快速，轻量级的跨平台的C++GUI工具包。[官网](http://www.fltk.org/index.php)
*   GTK+：用于创建图形用户界面的跨平台工具包。[官网](http://www.gtk.org/)
*   gtkmm：用于受欢迎的GUI库GTK+的官方C++接口。[官网](http://www.gtkmm.org/en/)
*   imgui：拥有最小依赖关系的立即模式图形用户界面。[官网](https://github.com/ocornut/imgui)
*   libRocket：[libRocket](http://librocket.com/) 是一个C++ HTML/CSS 游戏接口中间件。[官网](http://librocket.com/)
*   MyGUI：快速，灵活，简单的GUI。[官网](http://mygui.info/)
*   Ncurses：终端用户界面。[官网](http://invisible-island.net/ncurses/)
*   QCustomPlot：没有更多依赖关系的Qt绘图控件。[官网](http://qcustomplot.com/)
*   Qwt：用户与技术应用的Qt控件。[官网](http://qwt.sourceforge.net/)
*   QwtPlot3D：功能丰富的基于Qt/OpenGL的C++编程库，本质上提供了一群3D控件。[官网](http://qwtplot3d.sourceforge.net/)
*   OtterUI：[OtterUI](https://github.com/Twolewis/OtterUI) 是用于嵌入式系统和互动娱乐软件的用户界面开发解决方案。[官网](https://github.com/Twolewis/OtterUI)
*   PDCurses：包含源代码和预编译库的公共图形函数库。[官网](http://pdcurses.sourceforge.net/)
*   wxWidgets：C++库，允许开发人员使用一个代码库可以为widows， Mac OS X，Linux和其他平台创建应用程序。[官网](http://wxwidgets.org/)

### 图形

*   bgfx：跨平台的渲染库。[官网](https://github.com/bkaradzic/bgfx)
*   Cairo：支持多种输出设备的2D图形库。[官网](http://www.cairographics.org/)
*   Horde3D：一个小型的3D渲染和动画引擎。[官网](https://github.com/horde3d/Horde3D)
*   magnum：C++11和OpenGL 2D/3D 图形引擎。[官网](https://github.com/mosra/magnum)
*   Ogre 3D：用C++编写的一个面向场景，实时，灵活的3D渲染引擎（并非游戏引擎）。[官网](http://www.ogre3d.org/)
*   OpenSceneGraph：具有高性能的开源3D图形工具包。[官网](http://www.openscenegraph.org/)
*   Panda3D：用于3D渲染和游戏开发的框架，用Python和C++编写。[官网](http://www.panda3d.org/)
*   Skia：用于绘制文字，图形和图像的完整的2D图形库。[官网](https://github.com/google/skia)
*   urho3d：跨平台的渲染和游戏引擎。[官网](https://github.com/urho3d/Urho3D)

### 图像处理

*   [Boost.GIL](http://hao.jobbole.com/boost-gil/)：通用图像库。[官网](http://www.boost.org/doc/libs/1_56_0/libs/gil/doc/index.html)
*   CImg：用于图像处理的小型开源C++工具包。[官网](http://cimg.sourceforge.net/)
*   CxImage：用于加载，保存，显示和转换的图像处理和转换库，可以处理的图片格式包括 BMP, JPEG, GIF, PNG, TIFF, MNG, ICO, PCX, TGA, WMF, WBMP, JBG, J2K。[官网](http://www.xdp.it/cximage.htm)
*   FreeImage：开源库，支持现在多媒体应用所需的通用图片格式和其他格式。[官网](http://freeimage.sourceforge.net/)
*   GDCM：Grassroots DICOM 库。[官网](http://gdcm.sourceforge.net/wiki/index.php/Main_Page)
*   ITK：跨平台的开源图像分析系统。[官网](http://www.itk.org/)
*   Magick++：ImageMagick程序的C++接口。[官网](http://www.imagemagick.org/script/api.php)
*   MagickWnd：ImageMagick程序的C++接口。[官网](http://www.imagemagick.org/script/api.php)
*   [OpenCV](http://hao.jobbole.com/opencv/)：开源计算机视觉类库。[官网](http://opencv.org/)
*   tesseract-ocr：OCR引擎。[官网](https://code.google.com/p/tesseract-ocr/)
*   VIGRA：用于图像分析通用C++计算机视觉库。[官网](https://github.com/ukoethe/vigra)
*   VTK：用于3D计算机图形学，图像处理和可视化的开源免费软件系统。[官网](http://www.vtk.org/)

### 国际化

*   gettext：GNU `gettext`。[官网](http://www.gnu.org/software/gettext/)
*   IBM ICU：提供Unicode 和全球化支持的C、C++ 和Java库。[官网](http://site.icu-project.org/)
*   libiconv：用于不同字符编码之间的编码转换库。[官网](http://www.gnu.org/software/libiconv/)

### Json

*   frozen：C/C++的Json解析生成器。[官网](https://github.com/cesanta/frozen)
*   Jansson：进行编解码和处理Json数据的C语言库。[官网](https://github.com/akheron/jansson)
*   jbson：C++14中构建和迭代BSON data,和Json 文档的库。[官网](https://github.com/chrismanning/jbson)
*   JeayeSON：非常健全的C++ JSON库，只包含头文件。[官网](https://github.com/jeaye/jeayeson)
*   JSON++：C++ JSON 解析器。[官网](https://github.com/hjiang/jsonxx)
*   json-parser：用可移植的ANSI C编写的JSON解析器，占用内存非常少。[官网](https://github.com/udp/json-parser)
*   json11：一个迷你的C++11 JSON库。[官网](https://github.com/dropbox/json11)
*   jute：非常简单的C++ JSON解析器。[官网](https://github.com/amir-s/jute)
*   ibjson：C语言中的JSON解析和打印库，很容易和任何模型集成。[官网](https://github.com/vincenthz/libjson)
*   libjson：轻量级的JSON库。[官网](http://sourceforge.net/projects/libjson/)
*   PicoJSON：C++中JSON解析序列化，只包含头文件。[官网](https://github.com/kazuho/picojson)
*   qt-json：用于JSON数据和 QVariant层次间的相互解析的简单类。[官网](https://github.com/gaudecker/qt-json)
*   QJson：将JSON数据映射到QVariant对象的基于Qt的库。[官网](https://github.com/flavio/qjson)
*   RapidJSON：用于C++的快速JSON 解析生成器，包含SAX和DOM两种风格的API。[官网](https://github.com/miloyip/rapidjson)
*   YAJL：C语言中快速流JSON解析库。[官网](https://github.com/lloyd/yajl)
*   json：一个现代 C++ JSON解析库。语法更直观，集成更简单，经过严格测试的同时对内存效率、速度有深入地考虑。[官网](https://github.com/nlohmann/json)

### 日志

*   Boost.Log：设计非常模块化，并且具有扩展性。[官网](http://www.boost.org/doc/libs/1_56_0/libs/log/doc/html/index.html)
*   easyloggingpp：C++日志库，只包含单一的头文件。[官网](https://github.com/easylogging/easyloggingpp)
*   Log4cpp：一系列C++类库，灵活添加日志到文件，系统日志，IDSA和其他地方。[官网](http://log4cpp.sourceforge.net/)
*   templog：轻量级C++库，可以添加日志到你的C++应用程序中。[官网](http://www.templog.org/)
*   spdlog：高性能，只包含头文件。[官网](https://github.com/gabime/spdlog)

### 机器学习

*   Caffe：快速的神经网络框架。[官网](https://github.com/BVLC/caffe)
*   [CCV](http://hao.jobbole.com/ccv/)：以C语言为核心的现代计算机视觉库。[官网](https://github.com/liuliu/ccv)
*   mlpack：可扩展的C++机器学习库。[官网](http://www.mlpack.org/)
*   OpenCV：开源计算机视觉库。[官网](https://github.com/Itseez/opencv)
*   Recommender：使用协同过滤进行产品推荐/建议的C语言库。[官网](https://github.com/GHamrouni/Recommender)
*   SHOGUN：Shogun 机器学习工具。[官网](https://github.com/shogun-toolbox/shogun)
*   sofia-ml：用于机器学习的快速增量算法套件。[官网](https://code.google.com/p/sofia-ml/)

### 数学

*   Armadillo：高质量的C++线性代数库，速度和易用性做到了很好的平衡。语法和MatlAB很相似。[官网](http://arma.sourceforge.net/)
*   blaze：高性能的C++数学库，用于密集和稀疏算法。[官网](https://code.google.com/p/blaze-lib/)
*   ceres-solver：来自谷歌的C++库，用于建模和解决大型复杂非线性最小平方问题。[官网](http://ceres-solver.org/)
*   CGal：高效，可靠的集合算法集合。[官网](http://www.cgal.org/)
*   cml：用于游戏和图形的免费C++数学库。[官网](http://cmldev.net/)
*   Eigen：高级C++模板头文件库，包括线性代数，矩阵，向量操作，数值解决和其他相关的算法。[官网](http://eigen.tuxfamily.org/)
*   GMTL：数学图形模板库是一组广泛实现基本图形的工具。[官网](http://ggt.sourceforge.net/)
*   GMP：用于个高精度计算的C/C++库，处理有符号整数，有理数和浮点数。[官网](https://gmplib.org/)

### 多媒体

*   GStreamer：构建媒体处理组件图形的库。[官网](http://gstreamer.freedesktop.org/)
*   LIVE555 Streaming Media：使用开放标准协议(RTP/RTCP, RTSP, SIP) 的多媒体流库。[官网](http://www.live555.com/liveMedia/)
*   libVLC：libVLC (VLC SDK)媒体框架。[官网](https://wiki.videolan.org/LibVLC)
*   QtAv：基于Qt和FFmpeg的多媒体播放框架，能够帮助你轻而易举地编写出一个播放器。[官网](https://github.com/wang-bin/QtAV)
*   SDL：简单直控媒体层。[官网](http://www.libsdl.org/)
*   SFML：快速，简单的多媒体库。[官网](http://www.sfml-dev.org/)

### 网络

*   ACE：C++面向对象网络编程工具包。[官网](http://www.cs.wustl.edu/~schmidt/ACE.html)
*   Boost.Asio：用于网络和底层I/O编程的跨平台的C++库。[官网](http://think-async.com/)
*   Casablanca：C++ REST SDK。[官网](http://casablanca.codeplex.com/)
*   cpp-netlib：高级网络编程的开源库集合。[官网](http://cpp-netlib.org/)
*   Dyad.c：C语言的异步网络。[官网](https://github.com/rxi/dyad)
*   libcurl：多协议文件传输库。[官网](http://curl.haxx.se/libcurl/) 
*   Mongoose：非常轻量级的网络服务器。[官网](https://github.com/cesanta/mongoose)
*   Muduo：用于Linux多线程服务器的C++非阻塞网络库。[官网](https://github.com/chenshuo/muduo)
*   net_skeleton：C/C++的TCP 客户端/服务器库。[官网](https://github.com/cesanta/net_skeleton)
*   nope.c：基于C语言的超轻型软件平台，用于可扩展的服务器端和网络应用。 对于C编程人员，可以考虑node.js。[官网](https://github.com/riolet/nope.c)
*   Onion：C语言HTTP服务器库，其设计为轻量级，易使用。[官网](https://github.com/davidmoreno/onion)
*   POCO：用于构建网络和基于互联网应用程序的C++类库，可以运行在桌面，服务器，移动和嵌入式系统。[官网](https://github.com/pocoproject)
*   RakNet：为游戏开发人员提供的跨平台的开源C++网络引擎。[官网](https://github.com/OculusVR/RakNet)
*   Tuf o：用于Qt之上的C++构建的异步Web框架。[官网](https://github.com/vinipsmaker/tufao)
*   WebSocket++：基于C++/Boost Aiso的websocket 客户端/服务器库。[官网](https://github.com/zaphoyd/websocketpp)
*   ZeroMQ：高速，模块化的异步通信库。[官网](http://zeromq.org/)

### 物理学

粒子物理

*   Geant4: 粒子探测器模拟引擎。[官网](http://geant4.web.cern.ch)

动力学仿真引擎

*   Box2D：2D的游戏物理引擎。[官网](https://code.google.com/p/box2d/)
*   Bullet：3D的游戏物理引擎。[官网](https://github.com/bulletphysics/bullet3)
*   Chipmunk：快速，轻量级的2D游戏物理库。[官网](https://github.com/slembcke/Chipmunk2D)
*   LiquidFun：2D的游戏物理引擎。[官网](https://github.com/google/liquidfun)
*   ODE：开放动力学引擎-开源，高性能库，模拟刚体动力学。[官网](http://www.ode.org/)
*   ofxBox2d：Box2D开源框架包装器。[官网](https://github.com/vanderlin/ofxBox2d)
*   Simbody：高性能C++多体动力学/物理库，模拟关节生物力学和机械系统，像车辆，机器人和人体骨骼。[官网](https://github.com/simbody/simbody)

### 机器人学

*   MOOS-IvP：一组开源C++模块，提供机器人平台的自主权，尤其是自主的海洋车辆。[官网](http://moos-ivp.org/)
*   MRPT：移动机器人编程工具包。[官网](http://www.mrpt.org/)
*   PCL：点云库是一个独立的，大规模的开放项目，用于2D/3D图像和点云处理。[官网](https://github.com/PointCloudLibrary/pcl)
*   Robotics Library (RL)：一个独立的C++库，包括机器人动力学，运动规划和控制。[官网](http://www.roboticslibrary.org/)
*   RobWork：一组C++库的集合，用于机器人系统的仿真和控制。[官网](http://www.robwork.dk/jrobwork/)
*   ROS：机器人操作系统，提供了一些库和工具帮助软件开发人员创建机器人应用程序。[官网](http://wiki.ros.org/)

### 科学计算

*   FFTW：用一维或者多维计算DFT的C语言库。[官网](http://www.fftw.org/)
*   GSL：GNU科学库。[官网](http://www.gnu.org/software/gsl/)

### 脚本

*   ChaiScript：用于C++的易于使用的嵌入式脚本语言。[官网](https://github.com/ChaiScript/ChaiScript/)
*   Lua：用于配置文件和基本应用程序脚本的小型快速脚本引擎。[官网](http://www.lua.org/)
*   luacxx：用于创建Lua绑定的C++ 11 API。[官网](https://github.com/dafrito/luacxx)
*   SWIG：一个可以让你的C++代码链接到JavaScript、Perl、PHP、Python、Tcl和Ruby的包装器/接口生成器。[官网](http://www.swig.org/)
*   V7：嵌入式的JavaScript 引擎。[官网](https://github.com/cesanta/v7)
*   V8：谷歌的快速JavaScript引擎，可以被嵌入到任何C++应用程序中。[官网](http://code.google.com/p/v8/)

### 序列化

*   Cap'n Proto：快速数据交换格式和RPC系统。[官网](http://kentonv.github.io/capnproto/)
*   cereal：C++11 序列化库。[官网](https://github.com/USCiLab/cereal)
*   FlatBuffers：内存高效的序列化库。[官网](https://github.com/google/flatbuffers)
*   MessagePack：C/C++的高效二进制序列化库，例如 JSON。[官网](https://github.com/msgpack/msgpack-c)
*   protobuf：协议缓冲，谷歌的数据交换格式。[官网](http://code.google.com/p/protobuf/)
*   protobuf-c：C语言的协议缓冲实现。[官网](https://github.com/protobuf-c/protobuf-c)
*   SimpleBinaryEncoding：用于低延迟应用程序的对二进制格式的应用程序信息的编码和解码。[官网](https://github.com/real-logic/simple-binary-encoding)
*   Thrift：高效的跨语言IPC/RPC，用于C++，Java，Python，PHP，C#和其它多种语言中，最初由Twitter开发。[官网](https://thrift.apache.org/)

### 视频

*   libvpx：VP8/VP9编码解码SDK。[官网](http://www.webmproject.org/code/)
*   FFmpeg：一个完整的，跨平台的解决方案，用于记录，转换视频和音频流。[官网](https://www.ffmpeg.org/)
*   libde265：开放的h.265视频编解码器的实现。[官网](https://github.com/strukturag/libde265)
*   OpenH264：开源H.364 编解码器。[官网](https://github.com/cisco/openh264)
*   Theora：免费开源的视频压缩格式。[官网](http://www.theora.org/)

### 虚拟机

*   CarpVM：C中有趣的VM，让我们一起来看看这个。[官网](https://github.com/tekknolagi/carp)
*   MicroPython：旨在实现单片机上Python3.x的实现。[官网](https://github.com/micropython/micropython)
*   TinyVM：用纯粹的ANSI C编写的小型，快速，轻量级的虚拟机。[官网](https://github.com/jakogut/tinyvm)

### Web应用框架

*   Civetweb：提供易于使用，强大的，C/C++嵌入式Web服务器，带有可选的CGI，SSL和Lua支持。[官网](https://github.com/bel2125/civetweb)
*   CppCMS：免费高性能的Web开发框架（不是 CMS）。[官网](http://cppcms.com/)
*   Crow：一个C++微型web框架（灵感来自于Python Flask）。[官网](https://github.com/ipkn/crow)
*   Kore：使用C语言开发的用于web应用程序的超快速和灵活的web服务器/框架。[官网](https://kore.io/)
*   libOnion：轻量级的库，帮助你使用C编程语言创建web服务器。[官网](http://www.coralbits.com/libonion/)
*   QDjango：使用C++编写的，基于Qt库的web框架，试图效仿Django API，因此得此名。[官网](https://github.com/jlaine/qdjango/)
*   Wt：开发Web应用的C++库。[官网](http://www.webtoolkit.eu/wt)

### XML

XML就是个垃圾，XML的解析很烦人，对于计算机它也是个灾难。这种糟糕的东西完全没有存在的理由了。-Linus Torvalds

*   Expat：用C语言编写的XML解析库。[官网](http://www.libexpat.org/)
*   Libxml2：Gnome的XML C解析器和工具包。[官网](http://xmlsoft.org/)
*   libxml++：C++的XML解析器。[官网](http://libxmlplusplus.sourceforge.net/)
*   PugiXML：用于C++的，支持XPath的轻量级，简单快速的XML解析器。[官网](http://pugixml.org/)
*   RapidXml：试图创建最快速的XML解析器，同时保持易用性，可移植性和合理的W3C兼容性。[官网](http://rapidxml.sourceforge.net/)
*   TinyXML：简单小型的C++XML解析器，可以很容易地集成到其它项目中。[官网](http://sourceforge.net/projects/tinyxml/)
*   TinyXML2：简单快速的C++CML解析器，可以很容易集成到其它项目中。[官网](https://github.com/leethomason/tinyxml2)
*   TinyXML++：TinyXML的一个全新的接口，使用了C++的许多许多优势，模板，异常和更好的异常处理。[官网](https://code.google.com/p/ticpp/)
*   Xerces-C++：用可移植的C++的子集编写的XML验证解析器。[官网](http://xerces.apache.org/xerces-c/)

### 多项混杂

一些有用的库或者工具，但是不适合上面的分类，或者还没有分类

*   C++ Format：C++的小型，安全和快速格式化库。[官网](https://github.com/cppformat/cppformat)
*   casacore：从aips++ 派生的一系列C++核心库。[官网](https://code.google.com/p/casacore/)
*   cxx-prettyprint：用于C++容器的打印库。[官网](https://github.com/louisdx/cxx-prettyprint)
*   DynaPDF：易于使用的PDF生成库。[官网](http://www.dynaforms.com/)
*   gcc-poison：帮助开发人员禁止应用程序中的不安全的C/C++函数的简单的头文件。[官网](https://github.com/leafsr/gcc-poison)
*   googlemock：编写和使用C++模拟类的库。[官网](http://code.google.com/p/googlemock/)
*   HTTP Parser：C的http请求/响应解析器。[官网](https://github.com/joyent/http-parser)
*   libcpuid：用于x86 CPU检测盒特征提取的小型C库。[官网](https://github.com/anrieff/libcpuid)
*   libevil：许可证管理器。[官网](https://github.com/avati/libevil)
*   libusb：允许移动访问USB设备的通用USB库。[官网](http://www.libusb.org/)
*   PCRE：正则表达式C库，灵感来自于Perl中正则表达式的功能。[官网](http://pcre.org/)
*   Remote Call Framework：C++的进程间通信框架。[官网](http://www.deltavsoft.com/)
*   Scintilla：开源的代码编辑控件。[官网](http://scintilla.org/)
*   Serial Communication Library：C++语言编写的跨平台，串口库。[官网](https://github.com/wjwwood/serial)
*   SDS：C的简单动态字符串库。[官网](https://github.com/antirez/sds)
*   SLDR：超轻的DNS解析器。[官网](https://github.com/cesanta/sldr)
*   SLRE：超轻的正则表达式库。[官网](https://github.com/cesanta/slre)
*   Stage：移动机器人模拟器。[官网](https://github.com/rtv/Stage)
*   VarTypes：C++/Qt4功能丰富，面向对象的管理变量的框架。[官网](https://code.google.com/p/vartypes/)
*   ZBar：‘条形码扫描器’库，可以扫描照片，图片和视频流中的条形码，并返回结果。[官网](http://zbar.sourceforge.net/)
*   CppVerbalExpressions：易于使用的C++正则表达式。[官网](https://github.com/VerbalExpressions/CppVerbalExpressions)
*   QtVerbalExpressions：基于C++ VerbalExpressions 库的Qt库。[官网](https://github.com/VerbalExpressions/QtVerbalExpressions)
*   PHP-CPP：使用C++来构建PHP扩展的库。[官网](https://github.com/CopernicaMarketingSoftware/PHP-CPP)
*   Better String：C的另一个字符串库，功能更丰富，但是没有缓冲溢出问题，还包含了一个C++包装器。[官网](http://bstring.sourceforge.net/)

### 软件

用于创建开发环境的软件

### 编译器

C/C++编译器列表

*   Clang：由苹果公司开发的。[官网](http://clang.llvm.org/)
*   GCC：GNU编译器集合。[官网](https://gcc.gnu.org/)
*   Intel C++ Compiler：由英特尔公司开发。[官网](https://software.intel.com/en-us/c-compilers)
*   LLVM：模块化和可重用编译器和工具链技术的集合。[官网](http://llvm.org/)
*   Microsoft Visual C++：MSVC，由微软公司开发。[官网](http://msdn.microsoft.com/en-us/vstudio/hh386302.aspx)
*   Open WatCom：Watcom、C、C++和Fortran交叉编译器和工具。[官网](http://www.openwatcom.org/index.php/Main_Page)
*   TCC：轻量级的C语言编译器。[官网](http://bellard.org/tcc/)

### 在线编译器

在线C/C++编译器列表

*   codepad：在线编译器/解释器，一个简单的协作工具。[官网](http://codepad.org/)
*   CodeTwist：一个简单的在线编译器/解释器，你可以粘贴的C,C++或者Java代码，在线执行并查看结果。[官网](http://codetwist.com/)
*   coliru：在线编译器/shell， 支持各种C++编译器。[官网](http://coliru.stacked-crooked.com/)
*   Compiler Explorer：交互式编译器，可以进行汇编输出。[官网](http://gcc.godbolt.org/)
*   CompileOnline：Linux上在线编译和执行C++程序。[官网](http://www.compileonline.com/compile_cpp11_online.php)
*   Ideone：一个在线编译器和调试工具，允许你在线编译源代码并执行，支持60多种编程语言。[官网](http://ideone.com/)
*   C++ Shell:一个非常简单方便,不需要注册的C++在线编译器,可以显示编译信息,允许使用不同的C++标准,不同的优化选项,并支持stdio.[官网](http://cpp.sh)

### 调试器

C/C++调试器列表

*   Comparison of debuggers：来自维基百科的调试器列表。[官网](http://en.wikipedia.org/wiki/Comparison_of_debuggers)
*   GDB：GNU调试器。[官网](https://www.gnu.org/software/gdb)
*   Valgrind：内存调试，内存泄露检测，性能分析工具。[官网](http://valgrind.org/)

### 集成开发环境（IDE）

C/C++集成开发环境列表

*   AppCode：构建与JetBrains’ IntelliJ IDEA 平台上的用于Objective-C，C,C++，Java和Java开发的集成开发环境。[官网](http://www.jetbrains.com/objc/)
*   CLion：来自JetBrains的跨平台的C/C++的集成开发环境。[官网](http://www.jetbrains.com/clion/)
*   Code::Blocks：免费C，C++和Fortran的集成开发环境。[官网](http://www.codeblocks.org/)
*   CodeLite：另一个跨平台的免费的C/C++集成开发环境。[官网](http://codelite.org/)
*   Dev-C++：可移植的C/C++/C++11集成开发环境。[官网](http://sourceforge.net/projects/orwelldevcpp/)
*   Eclipse CDT：基于Eclipse平台的功能齐全的C和C++集成开发环境。[官网](http://www.eclipse.org/cdt/)
*   Geany：轻量级的快速，跨平台的集成开发环境。[官网](http://www.geany.org/)
*   IBM VisualAge：来自IBM的家庭计算机集成开发环境。[官网](http://www-03.ibm.com/software/products/en/visgen)
*   Irony-mode：由libclang驱动的用于Emacs的C/C++微模式。[官网](https://github.com/Sarcasm/irony-mode)
*   KDevelop：免费开源集成开发环境。[官网](https://www.kdevelop.org/)
*   Microsoft Visual Studio：来自微软的集成开发环境。[官网](http://www.visualstudio.com/)
*   NetBeans：主要用于Java开发的的集成开发环境，也支持其他语言，尤其是PHP，C/C++和HTML5。[官网](https://netbeans.org/)
*   Qt Creator：跨平台的C++，Javascript和QML集成开发环境，也是Qt SDK的一部分。[官网](http://qt-project.org/)
*   rtags：C/C++的客户端服务器索引，用于 跟基于clang的emacs的集成。[官网](https://github.com/Andersbakken/rtags)
*   Xcode：由苹果公司开发。[官网](https://developer.apple.com/xcode/)
*   YouCompleteMe：一个用于Vim的根据你敲的代码快速模糊搜索并进行代码补全的引擎。[官网](https://valloric.github.io/YouCompleteMe/)

### 构建系统

*   Bear：用于为clang工具生成编译数据库的工具。[官网](https://github.com/rizsotto/Bear)
*   Biicode：基于文件的简单依赖管理器。[官网](https://www.biicode.com/)
*   CMake：跨平台的免费开源软件用于管理软件使用独立编译的方法进行构建的过程。[官网](http://www.cmake.org/)
*   CPM：基于CMake和Git的C++包管理器。[官网](https://github.com/iauns/cpm)
*   FASTBuild：高性能，开源的构建系统，支持高度可扩展性的编译，缓冲和网络分布。[官网](http://www.fastbuild.org/docs/home.html)
*   Ninja：专注于速度的小型构建系统。[官网](http://martine.github.io/ninja/)
*   Scons：使用Python scipt 配置的软件构建工具。[官网](http://www.scons.org/)
*   tundra：高性能的代码构建系统，甚至对于非常大型的软件项目，也能提供最好的增量构建次数。[官网](https://github.com/deplinenoise/tundra)
*   tup：基于文件的构建系统，用于后台监控变化的文件。[官网](http://gittup.org/tup/)

### 静态代码分析

提高质量，减少瑕疵的代码分析工具列表

*   [Cppcheck](http://hao.jobbole.com/cppcheck/)：静态C/C++代码分析工具。[官网](http://cppcheck.sourceforge.net/)
*   [include-what-you-use](http://hao.jobbole.com/include-what-you-use/)：使用clang进行代码分析的工具，可以#include在C和C++文件中。[官网](https://code.google.com/p/include-what-you-use/)
*   OCLint：用于C，C++和Objective-C的静态源代码分析工具，用于提高质量，减少瑕疵。[官网](http://oclint.org/)
*   [Clang Static Analyzer](http://hao.jobbole.com/clang-static-analyzer/)：查找C，C++和Objective-C程序bug的源代码分析工具。[官网](http://clang-analyzer.llvm.org/index.html)
*   静态代码分析工具清单（[开源篇](http://hao.jobbole.com/static_code_analysis_tool_list_opensource/)）：来自维基百科的静态代码分析工具列表。[官网](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis#C.2FC.2B.2B)
   

<h3 id="weibo-weixin">微信公众号</h3>
* CPP开发者：专注分享 C/C++ 开发相关的技术文章和工具资源。
<br><img src="http://ww1.sinaimg.cn/small/63918611gw1epb2c4w55aj2046046t8t.jpg" width=150 height=150>

