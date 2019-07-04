# 10.13.14

成功驱动：
  1丶耳机并且无杂音
  2丶内置及USB健盘
  3丶有线网络
  4丶电量正常显示
  5丶CPU
  6丶内存条
  7丶INTEL集显
  
未驱动：
  1丶外接显示器
  2丶无线网卡
  3丶GT920MX独显
  4丶内置声卡（若去除相关hot patch则可正常发声，但耳机有杂音且音量过小）
  
我的配置：
  品牌：华硕顽石F441
  CPU：i57200U
  显卡：GT920MX
  声卡：ALC255
  网卡：
  
BIOS设置：
  load optimal
  disable secure boot 
  disable vt-d

已知问题：
  RealtekRTL8100.kext存在于/S/L/E中，虽然CLOVER中加入了RealtekRTL8111.kext， 但删除原驱动则重启后无法上网。
  一睡就死
  拔掉网线再接上则无法上网
