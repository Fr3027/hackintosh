# 10.14.5

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
  4丶内置声卡（若去除相关hot patch则可正常发声，但耳机有杂音且音量过小）
  5丶电量显示
  
我的配置：
  品牌：华硕顽石F441
  CPU：i57200U
  显卡：GT920MX
  声卡：ALC255
  网卡：
  
config.plist:
  layout-id=15
  Clover: r4972
BIOS设置：
  load optimal
  disable secure boot 
  disable vt-d

已知问题：
    一睡就死
    外接显示器直接重启
    电源显示拷贝原来的DSDT PATCH不行
  
