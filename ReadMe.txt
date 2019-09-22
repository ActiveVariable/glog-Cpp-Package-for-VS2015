Package usage instructions
In two simple steps, use GLOG in your C++ project:
1. Copy the Package folder to your project directory
2. In your project, open the Attribute Manager and add the corresponding attribute pages from Package/props to your project.
Note: 
1.Property pages can be uninstalled in Property Manager, but do not delete property pages directly into folders, otherwise the project will refuse to open.
2.Before Use:
#define GLOG_NO_ABBREVIATED_SEVERITIES
#define GOOGLE_GLOG_DLL_DECL
#include "glog/logging.h"
#include "glog/log_severity.h"
using namespace google;
3.Make minor modifications on glog, add the suffix ". log" to the log name, and surround the log level in the log entries with middle brackets for easy searching.

Package使用说明
简单两步,在你的C++工程中使用glog:
1、将Package文件夹拷贝到你的工程目录下
2、在你的工程中，打开属性管理器，从Package/props中添加相应的属性页到你的工程中
注意:
1.属性页可以在属性管理器中卸载，但不要直接到文件夹中删除属性页，否则会导致工程无法打开
2.使用之前:
#define GLOG_NO_ABBREVIATED_SEVERITIES
#define GOOGLE_GLOG_DLL_DECL
#include "glog/logging.h"
#include "glog/log_severity.h"
using namespace google;
3.在glog上做了小修改,日志名添加后缀.log，日志条目中的日志等级用中括号包围,便于查找

