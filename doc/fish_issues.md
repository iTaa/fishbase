fish_common 特性列表

last update: 2018.2.1 

####v1.0.10

* 19006，增加，get_time_uuid(), 获得带时间戳的流水号；ok
* 19007，增加，if_any_elements_is_space(),判断参数列表是否存在不合法的参数，如果存在 None 或空字符串或空格字符串，
    则返回True, 否则返回False；ok
* 19008，common，增加 conf_as_dict(),读入配置文件，返回根据配置文件内容生成的字典类型变量; 
* 11001，整体结构和开发方法调整；
* 11002, 增加 csv 功能模块，增加函数 csv_file_to_list(); ok
* 11003, fish_file 模块修改为 file，目前向下兼容保留 fish_file; ok
* 11004, file 模块的 get_abs_filename_with_sub_path() 修改；ok
* 11005, fish_date 模块修改为 date, demo/demo_date.py 演示用法；ok
* 11006, 安装包的安装程序 setup.py 中 setup.py 引入源的修改；ok
* 11007, pip 安装时候支持自动安装 python-dateutil 包; ok
* 11008, check_platform() 归入到 system 包
* 11009, csv, csv_file_to_list() 函数增加过滤空行功能；ok
 
---

####v1.0.9

* 19001, 增加，check_sub_path_create() 检查当前路径下的某个子路径是否存在, 不存在则创建；ok
* 19002, 修改，get_long_filename_with_sub_dir() 修改为 get_abs_filename_with_sub_path()；ok
* 19003, 修改，所有文件相关操作，转移到独立 py 文件; ok
* 19004, 修改，get_long_filename_with_sub_dir_module() 修改为 get_abs_filename_with_sub_path_module(); ok
* 19005, 修改，long_filename 都修改为 abd_filename; ok

---

包的编译上传等

* Run setup.py Task, chose sdist. The .tar.gz or .zip will appear under \dist path