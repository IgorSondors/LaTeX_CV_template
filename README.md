# LaTeX_CV_template

```python

\documentclass{article}
\usepackage{scimisc-cv}
\documentclass{book}
\usepackage[utf8]{inputenc}
\usepackage[english]{babel}

\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=blue,
}

\urlstyle{same}

\title{IgorSondors Recommended CV for ML Positions}
\author{IgorSondors}
\date{Oct 2020}

\cvname{Igor Sondors, ML engineer}
\cvpersonalinfo{
8(931)-57-69-201 \cvinfosep
igor.sondors@gmail.com \cvinfosep
\href{https://github.com/IgorSondors}{Github} \cvinfosep
\href{https://www.kaggle.com/igorsondors}{Kaggle} \cvinfosep
\href{https://www.linkedin.com/in/igor-sondors-06ba07b7/}{Linkedin}
}

\begin{document}


\makecvtitle %% This is a custom command constructing the CV title from \cvname, \cvpersonalinfo

\section{Summary}
\begin{itemize}
\item Interdisciplinary scientist with skills and experience in Solid state physics and Machine learning
\item Experienced school lecturer and private physics and mathematics teacher
\item Self-motivated, problem-solving and collaborative scientist with excellent communication skills
\item Looking to always study and improve my skills
\end{itemize}
 
\section{Technical Skills}

\begin{itemize}
\item \textbf{Python}
\item \textbf{Tensorflow} 
\item \textbf{LaTeX}  
\item \textbf{Wolfram Mathematica}
\item \textbf{OpenCV}
\item \textbf{SQL}
\item \textbf{Docker}
\end{itemize}
 
\section{Programmer Work Experience}

\cvsubsection{Aktiv financial group}[Saint Petersburg]
[ML engineer][Oct 2019 to present]

\begin{itemize}
\item I am built and conducted in production an OCR application for recognition of the Russian language text in documents. I use Tensorflow object detection API with fine tuning of Faster RCNN architecture for \href{https://github.com/IgorSondors/text_detector}{text detection} and CRNN model for text recognition on a noised images respectively.
\end{itemize}

\cvsubsection{GetLooky}[Saint Petersburg]
[ML engineer][Mar 2019 to Oct 2019]

\begin{itemize}
\item The task was to purify user question from unnecessary words then turn words in vectors and classify them. My contribution in this project is creating of \href{https://github.com/IgorSondors/getlooky_rnn_backend}{model} for classification of user questions using neural networks and classical machine learning methods.
\end{itemize}

 
\section{Education}

\begin{itemize}
\item Bachelor, Solid State Physics Department, Saint Petersburg State University, 2017  
\end{itemize}
 
\section{Teaching Experience }

\cvsubsection{Gostilitskaya school}[Saint Petersburg]
[Mathematics teacher][Sep 2018 to Aug 2019]

\begin{itemize}
\item I was a math teacher in pupil grades 10th and 11th. As a result of my work in this school all of graduates of the 11th grade passed the unified state exam with test score that better than the average in the Leningrad Region. One of my pupils reached a score of 90 in Mathematics exam. That great result provide of winning \href{https://gost-sch.lmn.su/index.php/tsentr-obrazovaniya-tsifrovogo-i-gumanitarnogo-profilej/galereya}{grant for the school}. So I decided to quit this job because I did teaching for six years and reach a state of the art in this.
\end{itemize}

\cvsubsection{Physics and Mathematics teacher}
[Private teacher][Sep 2013 to present]

\begin{itemize}
\item I \href{https://spb.repetitors.info/repetitor/?p=SondorsIK}{teach pupils} how to pass unified state exam of Mathematics and Physics and also university course of High Mathematics and Linear Algebra. I developed 5 training manuals for solve any geometric task and collect wide bank of physics tasks for ultimate exam training which efficient was proved 3 generations of my pupils. Pupils who were under my supervision were able to enter Moscow State University, St. Petersburg State University, Bauman Moscow State Technical University, Ural Federal University, etc
\end{itemize}

\section{Science Experience }

\cvsubsection{SPbSU Solid State Laboratory}[Saint Petersburg]
[Research engineer][Nov 2016 to Jan 2017]

\begin{itemize}
\item I researched of structure regularity and optical properties of nanowires which was grown at silicon and sapphire substrates. Also I was taking part with growing nano crystals on silicon and sapphire substrates and processed data on luminescence spectra which was near of theme of my diploma. My experience at this job was only for two months because I had to quit my job and focus on my diploma. Also I was working at I Physical lab and II Physical lab as a student and taking part at the \href{https://pureportal.spbu.ru/ru/projects/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D0%B2-%D1%84%D0%BE%D1%80%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B3%D0%B5%D1%82%D0%B5%D1%80%D0%BE%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80-%D0%BD%D0%B0-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5-iii}{grant researches of Silicon heterostructures}
\end{itemize}

\section{Other Skills}
\begin{description}[widest=Langauges]
\item[Languages]	English: professional proficiency.  Russian: native
\end{description}


\end{document}


```
