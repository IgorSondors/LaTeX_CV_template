# LaTeX_CV_template English

```latex

\documentclass{article}
\usepackage{scimisc-cv}
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
\item Always looking for study new things
\end{itemize}
 
\section{Technical Skills}

\begin{itemize}
\item \textbf{Python:} numpy, pandas, scikit-learn, xgboost, matplotlib, seaborn, opencv
\item \textbf{Tensorflow} 
\item \textbf{Wolfram Mathematica}
\item \textbf{SQL}
\item \textbf{Docker}
\item \textbf{LaTeX}
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
# LaTeX_CV_template Russian

```latex

\documentclass{article}
\usepackage{scimisc-cv}
\usepackage[english]{babel}
%Russian-specific packages
%--------------------------------------
\usepackage[T2A]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage[russian]{babel}
%--------------------------------------
\usepackage{hyperref}
\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    filecolor=magenta,      
    urlcolor=blue
}

\urlstyle{same}

\title{IgorSondors Recommended CV for ML Positions}
\author{IgorSondors}
\date{Oct 2020}

\cvname{Игорь Сондорс, ML engineer}
\cvpersonalinfo{
8(931)-57-69-201 \cvinfosep
igor.sondors@gmail.com \cvinfosep
\href{https://github.com/IgorSondors}{Github} \cvinfosep
\href{https://www.kaggle.com/igorsondors}{Kaggle} \cvinfosep
\href{https://www.linkedin.com/in/igor-sondors-06ba07b7/}{Linkedin}
}

\begin{document}


\makecvtitle %% This is a custom command constructing the CV title from \cvname, \cvpersonalinfo
 
\section{Технические навыки}

\begin{itemize}
\item \textbf{Python:} numpy, pandas, scikit-learn, xgboost, matplotlib, seaborn, opencv
\item \textbf{Tensorflow} 
\item \textbf{Wolfram Mathematica}
\item \textbf{SQL}
\item \textbf{Docker}
\item \textbf{LaTeX}
\end{itemize}
 
\section{Опыт программирования}

\cvsubsection{Финансовая группа "Актив"}[Санкт-Петербург]
[ML engineer][Октябрь 2019 по настоящее время]

\begin{itemize}
\item Создал OCR приложение работающее на облачном сервере для распознавания паспортов РФ по фото. Применил Tensorflow object detection API с тонкой настройкой архитектуры Faster RCNN для \href{https://github.com/IgorSondors/text_detector}{детектирования} и модель CRNN для распознания текста на шумных изображениях.
\end{itemize}

\cvsubsection{GetLooky}[Санкт-Петербург]
[ML engineer][Март 2019 по Октябрь 2019]

\begin{itemize}
\item Участвовал в разработке \href{https://github.com/IgorSondors/getlooky_rnn_backend}{системы} классификации вопросов пользователя с применением глубоких нейронных сетей и классических методов машинного обучения. Мой вклад этом проекте в создании самого классификатора.
\end{itemize}

\section{Преподавательский опыт}

\cvsubsection{Гостилицкая школа}[Санкт-Петербург]
[Учитель математики][Сентябрь 2018 по Август 2019]

\begin{itemize}
\item Работал учителем математики 10-11х классов общеобразовательной школы. Как результат моей работы, все ученики, которые сдавали профильный ЕГЭ по математике, написали экзамен с баллом выше среднего по ЛО, из тех учеников, которые сдавали экзамен базового уровня, не было ни одной оценки ниже 4. Один из моих учеников набрал 90 баллов на ЕГЭ. Подготовил двух медалистов, в том числе благодаря этому школа выиграла \href{https://gost-sch.lmn.su/index.php/tsentr-obrazovaniya-tsifrovogo-i-gumanitarnogo-profilej/galereya}{грант на ремонт}. Уволился из школы, так как эта работа перестала меня развивать.
\end{itemize}

\cvsubsection{Репетитор по математике и физике}
[][Сентябрь 2013 по настоящее время]

\begin{itemize}
\item Мною \href{https://spb.repetitors.info/repetitor/?p=SondorsIK}{написаны} 5 методических пособий для решения любых геометрических заданий из ЕГЭ по Математике, а также собран собственный банк заданий на все темы ЕГЭ по Физике. Мои ученики поступают в лучшие высшие учебные заведения страны: СПбГУ, МГУ, МГТУ им Баумана, УрФУ и др. Также ранее преподавал линейную алгебру и математический анализ студентам младших курсов.
\end{itemize}

\section{Научный опыт}

\cvsubsection{СПбГУ лаборатория Физики Твердого Тела}[Санкт-Петербург]
[Инженер-исследователь][Ноябрь 2016 по Январь 2017]

\begin{itemize}

\item Изучал правильность структуры и оптические свойства нитевидных нанокристаллов, что было близко к теме моей дипломной работы. Принимал участие в выращивании кристаллов GaN на кремниевой и сапфировой подложках. В данной должности я находился всего два месяца, так как был вынужден свое время полностью посвятить выпускной квалификационной работе. Также в курсе лабораторных работ я проводил различные опыты в I Физической и II Физической лабораториях и принимал участие в \href{https://pureportal.spbu.ru/ru/projects/%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D0%B2-%D1%84%D0%BE%D1%80%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%B3%D0%B5%D1%82%D0%B5%D1%80%D0%BE%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80-%D0%BD%D0%B0-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%B5-iii}{исследовании кремниевых гетеро-структур в рамках гранта}
\end{itemize}

\section{Образование}

\begin{itemize}
\item Бакалавр, Кафедра Физики Твердого Тела, Санкт-Петербургский Государственный Университет, 2017  
\end{itemize}
 
\section{Другие навыки}
\begin{description}[widest=Languages]
\item[Языки]	Английский: upper intermediate, достаточный для чтения документации и общения.  Русский: родной
\end{description}

\section{Награды}
\begin{itemize}
\item \href{https://daobet.org/blog/malta-blockchain-hackathon-event-review/}{Malta Blockchain Hackathon} в составе команды Tensegrity, Октябрь 2018
\item \href{https://www.kaggle.com/c/landmark-recognition-2020}{Google Landmark Recognition 2020}, Октябрь 2020
\end{itemize}

\end{document}

```
