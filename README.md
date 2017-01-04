# Chess
## Directory of chess中国象棋范例的源程序：目录src下的内容

> chess.dsw
chess.dsp

这两个是项目文件。包含整个项目的文件配置等信息
 
> chess.h
    这是应用程序的主头文件。包含了通用于工程的其他头文件。以及CChessApp类的声明。
> chess.cpp
    这是应用程序的主源程序。包含整个程序的入口点。CChessApp类的实现。

> chessDlg.h
chessDlg.cpp

这一对文件定义并实现了，象棋的主界面。

> StdAfx.h
StdAfx.cpp

这对文件由用于将一些预编译信息纳入程序。编译后将产生stdafx.obj

> resource.h
chess.rc

这是整个工程中使用的Windows资源列表。包括置于res子目录下的图标，位图以及光标等内容。

> define.h
	这是一个包含程序中的数据表示的定义的头文件。

> NewGame.h
NewGame.cpp
	这一对文件定义并实现用于新游戏的设置的对话框。

> Eveluation.h
Eveluation.cpp
	这一对文件定义并实现了估值核心类。

> MoveGenerator.h
MoveGenerator.cpp
	这一对文件定义并实现了走法产生器。

> SearchEngine.h
SearchEngine.cpp
	这一对文件定义了搜索引擎接口。
	
> NegamaxEngine.h
NegamaxEngine.cpp
	这一对文件定义并实现负极大值搜索引擎。
	
> AlphaBetaEngine.h
AlphaBetaEngine.cpp
	这一对文件定义并实现Alpha-Beta搜索引擎。

> IDAlphabeta.h
IDAlphabeta.cpp
	这一对文件定义并实现迭代深化的Alphabeta搜索引擎。

> FAlphaBetaEngine.h
FAlphaBetaEngine.cpp
	这一对文件定义并实现FAIL-SOFT Alphabeta搜索引擎。

> TranspositionTable.h
TranspositionTable.cpp
	这一对文件定义并实现置换表类。

> AlphaBetaAndTT.h
AlphaBetaAndTT.cpp
	这一对文件定义并实现Alpha-Beta+TT搜索引擎。

> FAlphaBetaAndTT.h
FAlphaBetaAndTT.cpp
	这一对文件定义并实现FAIL-SOFT+TT搜索引擎。

> PVS_Engine.h
PVS_Engine.cpp
	这一对文件定义并实现PVS搜索引擎。

> NegaScout.h
NegaScout.cpp
	这一对文件定义并实现NegaScout搜索引擎。

> AspirationSearch.h
AspirationSearch.cpp
	这一对文件定义并实现渴望搜索的搜索引擎。

> HistoryHeuristic.h
HistoryHeuristic.cpp
	这一对文件定义并实现历史启发类。

> Alphabeta_HH.h
Alphabeta_HH.cpp
	这一对文件定义并实现历史启发增强的Alphabeta搜索引擎。

> MTD_f.h
MTD_f.cpp
	这一对文件定义并实现MTD(f)搜索引擎。

> NegaScout_TT_HH.h
NegaScout_TT_HH.cpp
	这一对文件定义并实现历史启发和置换表增强的NegaScout搜索引擎。

## Directory of chess\res

chess.rc2//资源文件
chess.ico//图标文件
bitmap1.bmp//绘有棋盘的位图
bmp00001.bmp//绘有棋子的位图
