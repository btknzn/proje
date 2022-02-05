% Template for ICIP-2022 paper; to be used with:
%          spconf.sty  - ICASSP/ICIP LaTeX style file, and
%          IEEEbib.bst - IEEE bibliography style file.
% --------------------------------------------------------------------------
\documentclass{article}
\usepackage{spconf,amsmath,graphicx}

% Example definitions.
% --------------------
\def\x{{\mathbf x}}
\def\L{{\cal L}}

% Title.
% ------
\title{Semantic Segmentation application for Autonomous driving}
%
% Single address.
% ---------------
\name{ Sadok Kirac, Batu Kaan Oezen, Di Wu and Yigit Gurtunca \
}
\address{}
%
% For example:
% ------------
%\address{School\\
%	Department\\
%	Address}
%
% Two addresses (uncomment and modify for two-address case).
% ----------------------------------------------------------
%\twoauthors
%  {A. Author-one, B. Author-two\sthanks{Thanks to XYZ agency for funding.}}
%	{School A-B\\
%	Department A-B\\
%	Address A-B}
%  {C. Author-three, D. Author-four\sthanks{The fourth author performed the work
%	while at ...}}
%	{School C-D\\
%	Department C-D\\
%	Address C-D}
%
\begin{document}
%\ninept
%
\maketitle
%
\begin{abstract}
This project compares Fully Convolutional Networks, its deep versions  and DeepLab neural network architecture and investigate the way of training neural network with lowest possible amount of data and lowest GPU power. During this compression, FCN with Resnet34, FCN with Resnet50, FCN with Resnet 101 and DeepLab50 models are used.
\end{abstract}

\begin{keywords}
 Sementic Segmentation, Fully Convolutional Networks and DeepLab
\end{keywords}

\section{Introduction}
\label{sec:intro}
Increase of the interest on autonomous systems caused a need of more urgent development in Autonomous driving area but collecting semantic segmentation data is compare to other data set complicated. Even though big companies invested a lot of money on collecting  and made them open source, collecting appropriate data set might be impossible. In this project, it is investigated that increasing efficiency of models using small data sets and lower GPU power and proper solutions to solve this problem is found.  

\section{Research part of project}
\label{sec:format}


\section{Completed parts}
\label{sec:pagestyle}



\section{Evaluation}
\label{sec:typestyle}



\section{Results}
\label{sec:majhead}



\section{Recommendation for future development}
\label{sec:illust}





\section{REFERENCES}
1. https://arxiv.org/abs/1411.4038
2.https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Context_Encodin 
3.	 https://arxiv.org/abs/1706.05587
4.	https://arxiv.org/abs/2108.08810
6. https://ieeexplore.ieee.org/document/9106468


\end{document}
