# Latex_gougu
\documentclass[UTF8]{ctexart}

\title{浅谈勾股定理}
\author{张三}
\date{\today}

\usepackage{float}
\usepackage{graphicx}
\newtheorem{thm}{定理}
\bibliographystyle{plain}

\begin{document}

\maketitle
\begin{abstract}

简要介绍勾股定理

\end{abstract}
\tableofcontents
\section{勾股定理在古代}

远在公元前约三千年的古巴比伦人就知道和应用勾股定理，他们还知道许多勾股数组。


勾股定理是欧氏几何\footnote{欧几里得，公元前330--275年}的基础定理，并有巨大的实用价值．

这条定理不仅在几何学中是一颗光彩夺目的明珠，被誉为
23：“几何学的基石”，而且在高等数学和其他科学领域也有着广泛的应用．

1971年5月15日，尼加拉瓜发行了一套题为“改变世界面貌的十个数学公式”邮票，这十个数学公式由著名数学家选出的，勾股定理是其中之首

\begin{quote}

\zihao{-5}\kaishu   勾广三，股修四，径隅五

\end{quote}

\begin{figure}
   \centering
   \includegraphics[scale=0.1]{xingqiu.jpg}
   \caption{星球}
   \label{fig:xingqiu}
\end{figure}


\section{勾股定理在现在}


\begin{thm}[勾股定理]

直角三角形上的正方形等于直角边上的两个正方形之和

可以用符号语言表述为：设直角三角形ABC, $\angle C = 90^\circ$则有

\begin{equation}
AB^2 = BC^2 + AC^2
\end{equation}

\end{thm}

满足（1）的整数称为勾股数。下表列出一些较小的勾股数：

\begin{table}[H]
\begin{tabular}{|rrr|}
\hline
直角边  & 直角边  & 斜边\\
\hline
3 &  4  &  5\\
5 & 12 & 13\\
\hline
\end{tabular}%
\qquad
($a^2 + b^2 = c^2$)
\end{table}







\bibliography{math}



\end{document}