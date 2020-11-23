# Google-Breakpad
Linux下Qt中使用Google Breakpad捕获程序崩溃异常

该库为已经编译好的Google-Breakpad文件，直接下载放到QT的工程目录下，在QT工程配置文件(.pro)中添加库文件`libbreakpad_client.a`,

然后在代码里添加下面的头文件即可使用。：
```cpp
#include "client/linux/handler/exception_handler.h"
```

