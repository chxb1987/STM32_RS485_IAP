Flash分区：
	1、0X00000000 ~ 0X0800FBFF   前63K用于储存Bootload
	2、0X0800FC00 ~ 0X0800FFFF   第64K用于储存APP信息，包括是否需要升级，APP文件名，文件大小等
	3、0X08010000 ~ 0X08040000   后面的空间全部用于储存APP