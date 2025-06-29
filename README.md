# Resume-Code

%-------------------------
% Resume in Latex
% Author : Mrinmoy Low
% Website: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[pdftex]{hyperref}
\usepackage{fancyhdr}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.375in}
\addtolength{\evensidemargin}{-0.375in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING-----------------
\begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
  \textbf{\href{https://www.linkedin.com/in/mrinmoylow}{\Large Mrinmoy Low}} & Email : \href{mailto:mrinmoy.low2002@gmail.com}{mrinmoy.low2002@gmail.com}\\
  \href{https://www.linkedin.com/in/mrinmoylow}{LinkedIn Profile} & Mobile : +91 7001247496 \\
\end{tabular*}

%-----------OBJECTIVE-----------------
\section{Objective}
\resumeSubHeadingListStart
\item Seeking an opportunity to apply my skills and academic knowledge to contribute to an organization’s success, while gaining hands-on experience and further enhancing my professional growth.
\resumeSubHeadingListEnd

%-----------EDUCATION-----------------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Kalinga Institute of Industrial Technology}{Bhubaneshwar, Odisha}
      {Bachelor of Technology in Electronics and Computer Science Engineering | CGPA: 8.09/10}{August 2021 -- Present}
    \resumeSubheading
      {DAV Model School}{Durgapur, West Bengal}
      {CBSE Higher Secondary Education | Percentage: 81.4}{April 2019 -- March 2020}
    \resumeSubheading
      {DAV Model School}{Durgapur, West Bengal}
      {CBSE Secondary Education | Percentage: 88.1}{April 2017 -- March 2018}
  \resumeSubHeadingListEnd

%-----------EXPERIENCE-----------------
\section{Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Labmentix}{Remote}
      {AI/ML Intern}{June 2025 -- Present}
      \resumeItemListStart
        \resumeItem{Machine Learning Projects}
          {Developing and optimizing machine learning models to solve real-world challenges.}
        \resumeItem{AI Frameworks}
          {Gaining expertise in AI frameworks and deploying solutions to practical problems.}
      \resumeItemListEnd

    \resumeSubheading
      {Edunet Foundation - IBM SkillsBuild Program}{Remote}
      {AI Intern}{June 2025 -- Present}
      \resumeItemListStart
        \resumeItem{AI Tools}
          {Hands-on experience with IBM AI tools to address complex challenges.}
        \resumeItem{AI Solutions}
          {Collaborating on projects that involve model development and deployment.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

%-----------PROJECTS-----------------
\section{Projects}
  \resumeSubHeadingListStart
    \item {Developed practical AI and machine learning solutions, including a Python code generator, a house price prediction tool, and a text summarizer using advanced frameworks and deployment on cloud platforms.}
  \resumeSubHeadingListEnd

%--------CERTIFICATES------------
\section{Certificates}
\resumeSubHeadingListStart
  \item {Python For Beginners - Udemy}
  \item {5 Day Gen-AI Intensive Course - Kaggle}
\resumeSubHeadingListEnd

%--------ACHIEVEMENTS------------
\section{Achievements}
\resumeSubHeadingListStart
  \item {Solved Over 100+ questions on Leetcode.}
  \item {Ranked in the top candidates with an 80\% score in the semester exams.}
\resumeSubHeadingListEnd

%--------PROGRAMMING SKILLS------------
\section{Programming Skills}
 \resumeSubHeadingListStart
   \item{
     \textbf{Languages}{: Scala, Python, Javascript, C++, SQL, Java}
     \hfill
     \textbf{Technologies}{: AWS, Play, React, Kafka, GCE}
   }
 \resumeSubHeadingListEnd

%-------------------------------------------
\end{document}
