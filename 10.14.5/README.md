# 10.14.5

版本特性：
   # CLOVER和各个驱动必须更新到最新！
   MOJAVE移除了很多layout-id ,依旧可用的见下图：
   ![image](https://github.com/Fr3027/hackintosh/raw/master/imgs/layouts.png)
   另外可以在APPLEALC GITHUB上查看支持列表还有对应的layout-id , 两张图对着看，测试找出适合自己的layout-id
   MAC中查看ALC型号方法见我的onenote笔记！
成功驱动：
  1丶耳机并且无杂音
  2丶内置及USB健盘
  3丶有线网络
  4丶CPU
  5丶内存条
  6丶INTEL集显
  
未驱动：
  1丶外接显示器
  2丶无线网卡
  3丶GT920MX独显
  4丶内置声卡
  5丶电量显示
  
我的配置：
  品牌：华硕顽石F441
  CPU：i57200U
  显卡：GT920MX
  声卡：ALC255（使用IORegistryExplorer查看）
  网卡：
  
config.plist:
  基于Rehabman的 config_HD615_620_630_640_650.plist
  layout-id=15(耳机正常)
  layout-id=21(内置播放器正常)
  Clover: r4972
  
BIOS设置：
  load optimal
  disable secure boot 
  disable vt-d

已知问题：
    一睡就死
    外接显示器直接重启
    电源显示拷贝原来的DSDT PATCH不行
  
