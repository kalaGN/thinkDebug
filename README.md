将thinkPHP5.0中的debug类应用到自己的项目中，简单调试。
使用方法：
  1. 引入文件
  >include you/path/Debug.php
  2. 项目入口定义初始化变量
    >define('START_TIME', microtime(true));
  
  >define('START_MEM', memory_get_usage());
  3. 使用
  在需要调试的地方输出
  
  >echo  \think\Debug::getUseMem();
  
  >echo \think\Debug::getUseTime();
  
  >echo \think\Debug::getThroughputRate();
