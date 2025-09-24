# LaTeX online

[link](https://www.overleaf.com/)


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
\date{Mar 2023}

\cvname{Igor Sondors, ML engineer}
\cvpersonalinfo{
Telegram: @igorsondors \cvinfosep
igor.sondors@gmail.com \cvinfosep
\href{https://github.com/IgorSondors}{Github} \cvinfosep
\href{https://www.kaggle.com/igorsondors}{Kaggle} \cvinfosep
\href{https://www.linkedin.com/in/igor-sondors-06ba07b7/}{Linkedin}
}

\begin{document}


\makecvtitle %% This is a custom command constructing the CV title from \cvname, \cvpersonalinfo

\section{Technical Skills}

\begin{itemize}
\item \textbf{Python:} opencv, numpy, pandas, scikit-learn, xgboost, matplotlib, seaborn
\item \textbf{Tensorflow} 
\item \textbf{PyTorch}
\item \textbf{Docker}
\end{itemize}
 
\section{Programming Experience}

\cvsubsection{S8 Capital}[Moscow]
[ML engineer][Mar 2023 to present]

\begin{itemize}
\item Develop of a SKU-SKU ML matching system for e-commerce aggregator of merchandise prices

\end{itemize}

\cvsubsection{OzForensics}[Almaty]
[ML engineer][Dec 2021 to Mar 2023]

\begin{itemize}
\item Work on the development of models for evaluating the quality of pictures for a face recognition system and protection against spoofing of such systems. Made an ML model for assessing the of the user's eyes and smiles openness, made a model for protecting against the substitution of the camera's video stream.

\end{itemize}

\cvsubsection{Huawei Consumer Business Group}[Saint Petersburg]
[ML engineer][Dec 2020 to Dec 2021]

\begin{itemize}
\item The main part of my responsibilities is working with synthetic OCR generators and adaptation of those for our model training pipeline. Also my work includes research of any data augmentation modes and model training pipeline techniques

\end{itemize}

\cvsubsection{Aktiv financial group}[Saint Petersburg]
[ML engineer][Oct 2019 to Dec 2020]

\begin{itemize}
\item I built an OCR application for recognition of the Russian language text in documents.
\end{itemize}

\cvsubsection{GetLooky}[Saint Petersburg]
[Python programmer][Mar 2019 to Oct 2019]

\begin{itemize}
\item The task was to purify user questions from unnecessary words then turn words in vectors and classify them. My contribution in this project is creating a model for classification of user questions using neural networks and classical machine learning methods.
\end{itemize}
 
\section{Teaching Experience }

\cvsubsection{Gostilitskaya school}[Saint Petersburg]
[Mathematics teacher][Sep 2018 to Aug 2019]

\begin{itemize}
\item I was a math teacher in pupil grades 10th and 11th. As a result of my work in this school, all of the graduates of the 11th grade passed the unified state exam with test scores that were better than the average in the Leningrad Region. One of my pupils reached a score of 90 in the Mathematics exam. That great result provided a winning \href{https://gost-sch.lmn.su/index.php/tsentr-obrazovaniya-tsifrovogo-i-gumanitarnogo-profilej/galereya}{grant for the school}. So I decided to quit this job because I did teaching for six years and reached a state of the art in this.
\end{itemize}

\cvsubsection{Physics and Mathematics teacher}
[Private teacher][Sep 2013 to present]

\begin{itemize}
\item I \href{https://spb.repetitors.info/repetitor/?p=SondorsIK}{teach pupils} how to pass a unified state exam of Mathematics and Physics and also a university course of High Mathematics and Linear Algebra. I developed 5 training manuals for solving any geometric task and collected a wide bank of physics tasks for ultimate exam training which was proved by 3 generations of my pupils. Pupils who were under my supervision were able to enter Moscow State University, St. Petersburg State University, Bauman Moscow State Technical University, Ural Federal University, etc
\end{itemize}

\section{Science Experience }

\cvsubsection{SPbSU Solid State Laboratory}[Saint Petersburg]
[Research engineer][Nov 2016 to Jan 2017]

\begin{itemize}
\item I researched structure regularity and optical properties of nano wires which were grown at silicon and sapphire substrates. Also I was taking part in growing nano crystals on silicon and sapphire substrates and processed data on luminescence spectra which was near to the theme of my diploma. My experience at this job was only for two months because I had to quit my job and focus on my diploma. Also I was working at I Physical lab and II Physical lab as a student and taking part in the \href{https://pureportal.spbu.ru/ru/projects/modeling-of-formation-of-iiiv-nanowirebased-heterostructures-for-information-technologies-and-high-performance-computing(3d53fa04-1848-44ed-866c-2e067cc45b28).html}{research of GaN heterostructures}.
\end{itemize}

\section{Education}

\begin{itemize}
\item Bachelor, Solid State Physics Department, Saint Petersburg State University, 2017  
\end{itemize}

\section{Other Skills}
\begin{description}[widest=Langauges]
\item[Languages]	English: professional proficiency.  Russian: native
\end{description}

\section{Awards}
\begin{itemize}
\item Malta Blockchain Hackathon as a part of Tensegrity team, Oct 2018
\item \href{https://www.kaggle.com/c/landmark-recognition-2020}{Google Landmark Recognition 2020}, Oct 2020
\end{itemize}

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
Telegram: @igorsondors \cvinfosep
igor.sondors@gmail.com \cvinfosep
\href{https://github.com/IgorSondors}{Github} \cvinfosep
\href{https://www.kaggle.com/igorsondors}{Kaggle} \cvinfosep
\href{https://www.linkedin.com/in/igor-sondors-06ba07b7/}{Linkedin} \cvinfosep
\href{https://career.habr.com/igor-sondors}{Habr}
}

\begin{document}


\makecvtitle %% This is a custom command constructing the CV title from \cvname, \cvpersonalinfo
 
\section{Навыки}

\begin{itemize}
\item \textbf{Python:} opencv, numpy, pandas, scikit-learn, xgboost, transformers, matplotlib, seaborn
\item \textbf{DL:} PyTorch, Tensorflow, Keras
\item \textbf{Docker, Spark, Hadoop}
\item \textbf{English:} upper intermediate, достаточный для чтения документации и общения
\end{itemize}
 
\section{Программирование}

\cvsubsection{Т-банк}[Москва]
[ML engineer][Ноябрь 2024 по настоящее время]

\begin{itemize}
\item Разработал и внедрил в production NLP-сервис FLAI (First
Line AI) на базе BERT для авто классификации клиентских обращений в Т-бизнес. Backend: FastAPI, PostgreSQL, Kubernetes, CI/CD на GitLab. Полный DevOps-pipeline с мониторингом и Алертингом. Сервис снизил нагрузку на поддержку: высвобождено 4 FTE инженеров
\end{itemize}

\cvsubsection{S8 Capital}[Москва]
[ML engineer][Март 2023 по Октябрь 2024]

\begin{itemize}
\item Разработка \href{https://youtu.be/Esttc9j1bYk?si=leUdyXXYVqEZJzZN&t=4032}{ранжирующей и матчинговой системы} SKU-SKU
для агрегатора товаров price.ru. Генерация контента с
помощью LLM
\end{itemize}

\cvsubsection{OzForensics}[Алматы]
[ML engineer][Декабрь 2021 по Март 2023]

\begin{itemize}
\item Разработка моделей Quality Assessment для системы
распознавания лиц и моделей защиты от спуфинга таких
систем. Сделал ML модели оценки степени открытости глаз и
улыбки пользователя (Ordinal Regression), сделал нейросеть
для защиты от подмены видео потока с камеры  
\end{itemize}

\cvsubsection{Huawei Consumer Business Group}[Санкт-Петербург]
[ML engineer][Декабрь 2020 по Декабрь 2021]

\begin{itemize}
\item Разработка OCR in the wild, синтетические генераторы, препроцессинг плохо размеченных данных
(упорядочить облако точек), обучение моделей. Разработка
ML модели для выделения интересных моментов в видео
баскетбольных матчей (Temporal Shift Module).
\end{itemize}

\cvsubsection{Финансовая группа "Актив"}[Санкт-Петербург]
[ML engineer][Октябрь 2019 по Декабрь 2020]

\begin{itemize}
\item Разработка OCR системы для распознавания паспортов РФ
по фото. Применение CV без нейросетей, EasyOCR, Tesseract,
синтетические генераторы, обучение собственного OCR.
\end{itemize}

\cvsubsection{GetLooky}[Санкт-Петербург]
[Python programmer][Март 2019 по Октябрь 2019]

\begin{itemize}
\item Разработка системы классификации вопросов пользователя с
использованием classic ML алгоритмов.
\end{itemize}

\section{Преподавательство}

\cvsubsection{Гостилицкая школа}[Санкт-Петербург]
[Учитель математики][Сентябрь 2018 по Август 2019]

\begin{itemize}
\item Преподавал для 10-11х классов. Все мои ученики набрали баллы выше среднего по ЛО. Один из моих учеников набрал 90 баллов на ЕГЭ по математике. Я подготовил двух медалистов.
\end{itemize}

\cvsubsection{Репетитор по математике и физике}
[][Сентябрь 2013 по настоящее время]

\begin{itemize}
\item Мною написаны разработана авторская программа по подготовке к ЕГЭ по математике и физике. Мои ученики поступают в такие учебные заведения как СПбГУ, МГУ, МГТУ им Баумана, УрФУ.
\end{itemize}

\section{Наука}

\cvsubsection{СПбГУ лаборатория Физики Твердого Тела}[Санкт-Петербург]
[Инженер-исследователь][Ноябрь 2016 по Январь 2017]

\begin{itemize}

\item Изучал правильность структуры и оптические свойства
нитевидных нанокристаллов, что было близко к теме моей
дипломной работы. Принимал участие в выращивании
кристаллов GaN на кремниевой и сапфировой подложках.
Участвовал в \href{https://pureportal.spbu.ru/en/projects/modeling-of-formation-of-iiiv-nanowirebased-heterostructures-for-information-technologies-and-high-performance-computing(3d53fa04-1848-44ed-866c-2e067cc45b28).html}{грантовом исследовании}
\end{itemize}

\section{Образование}

\begin{itemize}
\item Бакалавр, Кафедра Физики Твердого Тела, Санкт-Петербургский Государственный Университет, 2017  
\end{itemize}

\section{Награды}
\begin{itemize}
\item Malta Blockchain Hackathon в составе команды Tensegrity, Октябрь 2018
\item \href{https://www.kaggle.com/c/landmark-recognition-2020}{Google Landmark Recognition 2020}, Октябрь 2020
\end{itemize}

\end{document}

```
