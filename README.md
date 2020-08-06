# Algorithms


Personal solutions to the problems that I find interesting


Conclusion:
1. DFS 可用queue和递归，用queue在queue不为空时始终继续，在子情况循环前pop
2. dp: 接龙型 (一个容器存储index前的全局最值，一个容器存储必须包含index的index前的最值)
   dp: 消除型/游戏法则等价型 (容器存储一定范围内的最优情形)
   dp: 博弈型 (容器存储的我这一步的最优情况是知道了下一步对手会选择的的最优情况下我此时的最优情况)
   dp: 估值型 (写一个helper函数，然后二分查找 O(nlogn))
3. graph遍历 (vector存储路径，set存储用过的点判断递归结束)

