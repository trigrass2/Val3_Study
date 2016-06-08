#程序说明#
##MoveID## 
1. MoveID是当前已经运动过的运动指令的值，根据设定的值进行自动叠加
2. 一条movej,movel,movec的moveid各为1
3. 运动指令的moveid与blend息息相关
4. reach决定moveid的下限，leave决定moveid的上限
5. waitendmove的上限为1
6. 相同的位置的moveid也叠加,查看SameInstruct
7. setmoveid(num) num必须是自然数
8. 运动堆栈的大小

