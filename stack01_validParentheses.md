# 思路：

1. 设置栈：左边入栈，右边遇到匹配的出栈，遇到不匹配的就凉了，遍历结束判断栈是否为空

2. 通过obj的key-value值进行左右匹配

3. 栈的实现：string：入栈+出栈subString(0,length-1)或array:入栈push，出栈pop
