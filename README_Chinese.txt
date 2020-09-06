算法可执行文件为PCPT-FCI.exe， 使用Microsoft Visual Studio 2010编译

-------------------------------------------------------------------------------

算法小例子为test.txt

数据集格式：

第1行为transaction总数，接下来每行第1位是本行包含的item数，其余为item

-------------------------------------------------------------------------------

使用命令行的执行程序参数如下：

PCPT-FCI.exe WINDOW_SIZE MINSUP INPUTFILE OUTPUTFILE SLIDING_NUMBER

其中：
WINDOW_SIZE ：窗口大小
MINSUP ：最小支持度
INPUTFILE ：输入文件（即数据集）
OUTPUTFILE ：输出文件
SLIDING_NUMBER：窗口滑动次数

例子：

PCPT-FCI.exe 4 1 test.txt out.txt 2