>  虽然很简单但是会有用的GBK, GB2312 汉字字符集和拼音码表

用于在嵌入式平台上进行搜索输入法制作和字库制作， 以及LD3320语音识别指令还原等等。仅需要大约 255kb ROM(一级常用汉字仅需150kb左右) 可以存储字库,  同时只使用少量const 变量, 实现外部存储拼音码表和检索。

**注意: 其中拼音码表GB2312的最全, 其他部分的仅有少量缺失, 如果使用, 可以以GB2312拼音码表为标准进行增补, 具体可参考下面**

V1.1 : GB2312 拼音码表增补: 谁水睡税匚冫冖阝凵廾擗辶屮肀钅疒衤虍

V1.2 : GB2312 拼音码表: 将 c, z, 以及 s 三个字打头的拼音部分进行合并
