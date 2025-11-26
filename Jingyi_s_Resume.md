%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% "ModernCV" CV and Cover Letter
% LaTeX Template
% Version 1.1 (9/12/12)
%
% This template has been downloaded from:
% http://www.LaTeXTemplates.com
%
% Original author:
% Xavier Danaux (xdanaux@gmail.com)
%
% License:
% CC BY-NC-SA 3.0 (http://creativecommons.org/licenses/by-nc-sa/3.0/)
%
% Important note:
% This template requires the moderncv.cls and .sty files to be in the same 
% directory as this .tex file. These files provide the resume style and themes 
% used for structuring the document.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%	PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------------------------------------------------

\documentclass[11pt,a4paper,sans]{moderncv} % Font sizes: 10, 11, or 12; paper sizes: a4paper, letterpaper, a5paper, legalpaper, executivepaper or landscape; font families: sans or roman
\usepackage{standalone}
\usepackage{tabularx,booktabs,ragged2e}
\usepackage{siunitx}              % 千位分隔符
\newcolumntype{L}{>{\RaggedRight\arraybackslash}X}
\newcolumntype{R}{>{\RaggedLeft\arraybackslash}X}


\moderncvstyle{classic} % CV theme - options include: 'casual' (default), 'classic', 'oldstyle' and 'banking'
\moderncvcolor{blue} % CV color - options include: 'blue' (default), 'orange', 'green', 'red', 'purple', 'grey' and 'black'

\usepackage{lipsum} % Used for inserting dummy 'Lorem ipsum' text into the template

\usepackage[scale=0.85]{geometry} % Reduce document margins
%\setlength{\hintscolumnwidth}{3cm} % Uncomment to change the width of the dates column
%\setlength{\makecvtitlenamewidth}{10cm} % For the 'classic' style, uncomment to adjust the width of the space allocated to your name

%\usepackage[utf8]{inputenc}

\usepackage{booktabs}
\usepackage{fontawesome}
\usepackage{marvosym} % For cool symbols.
%\usepackage{hyperref}




%----------------------------------------------------------------------------------------
%	NAME AND CONTACT INFORMATION SECTION
%----------------------------------------------------------------------------------------
\vspace{-1cm}
\firstname{Jingyi} % Your first name
\familyname{Zhao} % Your last name

% All information in this block is optional, comment out any lines you don't need
%\title{Postdoc Application Resume}



%\fax{(000) 111 1113}
 
%\social{github}{stefano-bragaglia}

\email{Email:zhaojingyi@cuhk.edu.cn} 



\extrainfo{
Birthday: 1997-02-15\\
    \faGithub\ Homepage: jingyi-poly.github.io\\
    \faPhone Phone: 18504319009 \\
    Google Scholar: scholar.google.com/citations?user=YkPRtnoAAAAJ\&hl=en
}



%\social[linkedin][www.linkedin.com]{name}
% The first argument is %the url for the clickable link, the second argument is the url displayed in the %template - this allows special characters to be displayed such as the tilde in this %example

\photo[100pt][0.5pt]{jy} % The first bracket is the picture height, the second is %the thickness of the frame around the picture (0pt for no frame)
%\quote{Not Attention, Patience is all we need.}

%----------------------------------------------------------------------------------------

\newcommand{\cvdoublecolumn}[2]{%
  \cvitem[.75em]{}{%
    \begin{minipage}[t]{\listdoubleitemcolumnwidth}#1\end{minipage}%
    \hfill%
    \begin{minipage}[t]{\listdoubleitemcolumnwidth}#2\end{minipage}%
    }%
}



\usepackage{multibbl}
\newcommand\Colorhref[3][orange]{\href{#2}{\small\color{#1}#3}}


% \newcommand{\cvreference}[7]{%
%     \textbf{#1}\newline% Name
%     \ifthenelse{\equal{#2}{}}{}{\addresssymbol~#2\newline}%
%     \ifthenelse{\equal{#3}{}}{}{#3\newline}%
%     \ifthenelse{\equal{#4}{}}{}{#4\newline}%
%     \ifthenelse{\equal{#5}{}}{}{#5\newline}%
%     \ifthenelse{\equal{#6}{}}{}{\emailsymbol~\texttt{#6}\newline}%
%     \ifthenelse{\equal{#7}{}}{}{\phonesymbol~#7}}

\begin{document}

\makecvtitle % Print the CV title




%----------------------------------------------------------------------------------------
%	EDUCATION SECTION
%----------------------------------------------------------------------------------------
\vspace{-1cm}



\section{EDUCATION}


\cventry{08/2019--05/2023}{Doctor of Philosophy (PhD), Industrial and Systems Engineering}{National University of Singapore}{}{}
{}  % Arguments not required can be left empty

\cventry{2015--2019 :}{Bachelor of Computing in Computer Science}{Northwestern Polytechnical University of China}{}{}{}
%{Advanced exposure to various areas of computer science along with a one and half year research project on Reversible Logic Synthesis.}
%\cvitem{CGPA :}{7.96/10}
%\cventry{2009--2013 :}{Bachelor of Engineering, Computer Science \& Technology}{Indian Institute of Engineering Science \& Technology}{Shibpur(\textit{Formerly} Bengal Engineering and Science University, Shibpur)}{}{}
%{Comprehensive exposure to the core areas of Computer Science along with a final year project on Data-mining}
%\cvitem{CGPA :}{7.36/10}
% \cventry{2008 :}{Higher Secondary Examination}{Belmuri Union Institution}{Belmuri}{}{ Mathematics, Physics, Chemistry, Biology, English, Bengali}
% {}
% \cvitem{Percentage :}{81.2 \%}
% \cventry{2006 :}{Secondary Examination}{Belmuri Union Institution}{Belmuri}{}{ Mathematics, Physical Science, Life Science, Geography, History, English, Bengali}
% {}
% \cvitem{Percentage :}{90.8 \%}





%----------------------------------------------------------------------------------------
%	PUBLICATION SECTION
%----------------------------------------------------------------------------------------
\section{WORK}
\cventry{06/2024 -- present:}{Research Scientist}{Department of Solver Development, Shenzhen Research Institute of Big Data (task: develop optimization solver)}{}{}{}
\cventry{06/2023 -- 06/2024:}{Postdoctoral Fellow}{Department of Mathematics and Industrial Engineering, Polytechnique Montréal (task: publish one paper)}{}{}{}

\section{INTERESTED AREA}

\cvitem{1.}{Integrated learning to optimize for solving dynamic and/or stochastic problems.}
\cvitem{2.}{Design effective methods based on data structures and algorithms for NP-hard problems.}
\cvitem{3.}{GPU-based accelerated algorithm solving large-scale scenario stochastic problems.}  
\cvitem{4.}{Combining OR technology with other fields, for example, with energy or with genetic screening for biological cancers.}  
%----------------------------------------------------------------------------------------
%	Teaching Assistantship SECTION
%----------------------------------------------------------------------------------------






\section{PUBLICATIONS}
% \subsection{Journal Article(Accepted)}
% \cventry{2019}{\textbf{Pratik Dutta}, Sriparna Saha, Sanket Pai and Aviral Kumar}{}{Protein-protein Interaction based Generative Model for Improving Gene Clustering}{at \textit{\textbf{Scientific Reports-Nature}} (\textbf{Impact Factor: 4.12)}}{}

\subsection{\textbf{\textcolor{blue}{JOURNAL PAPERS}}}
\cventry{2025}{
\underline{\textit{Jingyi Zhao*}},  Claudia Archetti,Tuan Anh Pham, Thibaut Vidal}{}{Large Neighborhood and Hybrid Genetic Search for Inventory Routing Problems}{Minor Revision at \textit{European Journal of
Operational Research}}{}

\cventry{2025}{
\underline{\textit{Jingyi Zhao}}, Zirong Zeng, Yang Liu*}{}{Electric Vehicle Routing Problem Considering Traffic Conditions and Real-time Loads}{ \textit{Transportation Research Part C: Emerging Technologies}}{}

\cventry{2024}{\underline{\textit{Jingyi Zhao}}, Mark Poon, Vincent Y. F. Tan, Zhenzhen Zhang*}{}{A Hybrid Genetic Search and Dynamic Programming-based Split Algorithm for the Multi-trip Time-dependent Vehicle Routing Problem}{European Journal of Operational Research}{}
\cventry{2022}{\underline{\textit{Jingyi Zhao}}, Mark Poon , Zhenzhen Zhang* , Ruixue Gu}{}{Adaptive Large Neighborhood Search for the Time-dependent Profitable Dial-a-ride Problem}{ Computers \& Operations Research}{}

\cventry{2025}{Kai Yang, Zhenzhen Zhang*, \underline{\textit{Jingyi Zhao}}, Zhe Liang}{}{A Neighborhood-based Mathematical Heuristic for the Vehicle Routing Problem with Delivery Options}{Transportation Research Part E: Logistics and Transportation Review}{}
\cventry{2023}{Weiquan Wang* \underline{\textit{Jingyi Zhao}}}{}{Partial Linear Recharging Strategy for the Electric Fleet Size and Mix Vehicle Routing Problem with Time Windows and Recharging Stations
}
{European Journal of Operational Research}{}





\subsection{\textbf{\textcolor{blue}{CONFERENCE PAPERS}}}

\cventry{2024}{
\underline{\textit{Jingyi Zhao}}, Linxin Yang, Haohua Zhang, Tian Ding*}{}{GPU-based Split algorithm for Large-Scale CVRPSD}{ \textit{ScaleOPT: GPU-Accelerated and Scalable Optimization
NeurIPS 2025 Workshop}}{}


\cventry{2024}{Runze Ni, \underline{\textit{Jingyi Zhao*}}}{}{Enhancing Urban Intelligent Traffic Simulations of Human-driven Car-following Behavior Using Deep Learning Techniques}{ \textit{The 24th COTA International Conference of Transportation Professionals (CICTP 2024)}}{}


\cventry{2024}{
\underline{\textit{Jingyi Zhao*}}, Thibaut Vidal}{}{A Hybrid Genetic Algorithm for the Inventory Routing Problem}{ \textit{The Ninth International Workshop on Freight Transportation and Logistics (ODYSSEUS Conference 2024)}}{}









\subsection{\textbf{\textcolor{blue}{PAPERS UNDER REVIEW}}}




\cventry{2025}{
\underline{\textit{Jingyi Zhao}}, Linxin Yang, Haohua Zhang, Qile He, Tian Ding}{}{From Sequential to Parallel: Reformulating Dynamic Programming as GPU Kernels for Large-Scale Stochastic Combinatorial Optimization}{Under Revision at \textit{ICLR 2026}}{}



\cventry{2024}{ Jianhua Xiao, Detian Kong, Zhiguang Cao, \underline{\textit{Jingyi Zhao*}} 
}{}{Deep Reinforcement Learning for the Vehicle
Routing Problem with Route Balancing}{1st revision at \textit{Transportation Research Part E: Logistics and Transportation Review}}{}


\cventry{2024}{Yaping Zhao, Xuewen Lei, Xinyue Zhang, \underline{\textit{Jingyi Zhao*}}
}{}{Machine Learning-Enhanced Rolling Horizon Optimization Algorithm for Dynamic Scheduling in AGV-Supported Rice Production}{at \textit{Omega}}{}

\subsection{\textbf{\textcolor{blue}{JOURNAL PAPERS in Progress}}}
\cventry{2024-2025}{
\underline{\textit{Jingyi Zhao}}, Youxuan Pan, Haoxiang Yang, Yang Liu*}{}{Large Neighborhood Search and Bitmask Dynamic Programming for Dynamic Mobile Charging Electric Vehicle Routing Problems in Medical Transportation}{}{}

\cventry{2024-2025}{
\underline{\textit{Jingyi Zhao}}, Kris Braekers, Youxuan Pan, Haoxiang Yang*}{}{A Mathematical Heuristic Method for Time-Dependent Vehicle Routing Problem Integrating Autonomous Electric Vehicles and Shared Distribution Locations}{}{}

\cventry{2025}{ \underline{\textit{Jingyi Zhao}}, Haoxiang Yang
}{}{Learning to Generate Lagrangian Cut for Two-stage
Stochastic Mixed-integer Programs}{}{}



\cventry{2024-2026}{ \underline{\textit{Jingyi Zhao}}, Xianzhi Wu, Daniele Vigo, Zhenzhen Zhang*
}{}{Learning to search in the configuration of s stochastic vehicle routing problem with packing containers under demand uncertainty }{}{}

\cventry{2024-2026}{\underline{\textit{Jingyi Zhao}}, Hongjun Chen, Bo Tang*
}{}{Combinatorial Optimization and Machine Learning
for Multi-stage Stochastic Inventory Routing}{}{}


\cventry{2024-2026}{\underline{ \textit{Jingyi Zhao}}, Xiaodong Luo, Juan Chen, Dong Zhang*
}{}{Parallel Evaluation of Large-scale Pickup and Delivery Problem with Time Window}{}{}



\cventry{2024-2026}{\underline{ \textit{Jingyi Zhao*}}, Theo Guyard, and Thibaut Vidal
}{}{Large Neighborhood and Hybrid Genetic Search for 2-stage Stochastic Inventory Routing Problem}{}{}

\cventry{2024-2025}{Hanrui Ye, \underline{\textit{Jingyi Zhao}}, Haoxiang Yang*
}{}{Integrated Learning and Optimization of Bidding Strategies in
Renewable Energy Electricity Markets}{}{}


\cventry{2024}{ Bo Tang, \underline{\textit{Jingyi Zhao}}, Elias B. Khalil*, Jan Drgona
}{}{Learning to Optimize for Mixed-Integer Nonlinear Programming}{}{}


\section{SCIENTIFIC TALKS}

\cvitem{2024}{ A hybrid genetic algorithm for the inventory routing problem (Odysseus 2024, Spain)}
\cvitem{2025}{ An Enhanced Learning-to-Optimize Framework for the Stochastic Inventory Routing Problem (International Conference on Stochastic Programming 2025, France)}

\cvitem{2025}{ GPU-accelerated Dynamic Programming for the Large-scaled Stochastic Inventory Routing Problem (Poms China 2025,China)}

\section{AWARDS}
\cvitem{2025}{Runner-up of Counterfactual Routing Competition CRC 25\@ 34th International Joint Conference on Artificial Intelligence (IJCAI 2025))}

\cvitem{2023}{ Best Paper Award in the 14th Workshop on Computational Transportation Science (CTS 2023)}

\cvitem{2017}{Golden medal in ACM-ICPC Asia Regional Contest (2017, Qingdao)}
\cvitem{2017}{Golden medal in ACM-ICPC Asia Regional Contest (2017, Nanning)}
\cvitem{2016}{ Silver medal in ACM-ICPC Asia Regional Contest (2016, Qingdao)}

\section{TEACHING EXPERIENCE}
\cventry{2020-2022:}{Modeling for Supply Chain Systems}{}{ISEM, National University of Singapore}{}{}
\cventry{2025-2026:}{Data, Modeling, and Decisions}{}{ Shenzhen Research Institute of Big Data }{}{}


\section{SKILLS}

\cvitem{Languages}{C++, Python,  Julia}
\cvitem{Algorithms}{Heuristic Algorithms, Dynamic Programing, Graph Theory, Benders Deposition}
\cvitem{Server}{Gurobi, Google OR-tools, Bonmin, COPT}


%----------------------------------------------------------------------------------------
%	Position of Responsibility SECTION
%----------------------------------------------------

\section*{FUNDINGS}
{\small
\begin{tabular}{@{}lcccc@{}}
\toprule
Project title & My role & Funding body & Budget (RMB) & Period\\
\midrule
Reservoir Optimization Algorithms & PI & Shenzhen Water Affairs Bureau & 1,200,000 & 2025.11--2026.11\\
MILP Solver Development & Researcher & Shenzhen Big-Data Inst & 600,000 & 2025.06--2026.12\\
Large-Scale MIP Algorithms & Researcher & National Key R\&D Program of China & 5,000,000 & 2023.01--2028.01\\
\bottomrule
\end{tabular}}


\section*{SUPERVISION}
\cvitem{Co-supervise}{ Xinyue Zhang, Master student at Wuhan Univerisity}
\cvitem{Co-supervise}{ Tingting Su, Ph.D student at Department of
Research group Logistics,
Hasselt University, Belgium}
\cvitem{Co-supervise}{Jiwei Zhang, Ph.D student at The Chinese University of Hong Kong (Shenzhen)}
\cvitem{Co-supervise}{Xingyan Shi, Ph.D student at The Chinese University of Hong Kong (Shenzhen)}



\section{REFEREES}


\begin{tabular}{lr}
% Referee 1
\begin{minipage}[t]{3in}
\textbf{Dr. Haoxiang Yang}\\
\textit{Assistant Professor,} \\
\textit{ School of Data Science,}\\
 {\small The Chinese University of Hong Kong, Shenzhen}\\
\Letter\ \href{yanghaoxiang@cuhk.edu.cn}{yanghaoxiang@cuhk.edu.cn}
\end{minipage}
&
% Referee 2
\begin{minipage}[t]{3in}
\textbf{Dr. Vincent Tan}\\
\textit{Professor, } \\
\textit{Department of Electrical and Computer Engineering}\\
National University of Singapore, Singapore \\
\Letter\ \href{vtan@nus.edu.sg}{vtan@nus.edu.sg}
\end{minipage}
\\
\\ % Additional newline for spacing.
% Referee 3
\begin{minipage}[t]{3in}
\textbf{Dr. Kris Braekers}\\
\textit{Professor, Department of} \\
\textit{Research group Logistics, \\Hasselt University, Belgium}\\
%Company: Integrated Decision Systems\\ Consultancy Pte Ltd\\
%\Telefon\ +(601) 877-6236\\
\Letter\ \href{kris.braekers@uhasselt.be}{kris.braekers@uhasselt.be}
\end{minipage}
&
\begin{minipage}[t]{3in}
\textbf{Dr. Thibaut Vidal}\\
\textit{Associate Professor,} \\
\textit{ SCALE-AI Chair in Data-Driven Supply Chains \& Department of Mathematics and Industrial Engineering (MAGI).}\\
Polytechnique Montréal, Canada\\
\Letter\ \href{thibaut.vidal@polymtl.ca}{thibaut.vidal@polymtl.ca}
\end{minipage}
\\

\end{tabular}


\end{document}