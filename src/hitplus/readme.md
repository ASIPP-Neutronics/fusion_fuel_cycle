# 功能描述
给定一个参数名，能够得到其下一级（仅限一级）的所有参数名
# 实现方式
修改了main.cc文件，添加了outputParam函数，主要是依赖于Node中的find、children等函数实现的功能
# 使用方式
1. 打开hitplus文件夹
2. 输入指令 ./hitplus output Openmodelica/iss ./example.i