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
\item \textbf{Python:} opencv, numpy, pandas, scikit-learn, xgboost, transformers, matplotlib, seaborn
\item \textbf{DL} PyTorch, Tensorflow, Keras
\item \textbf{Docker, Spark, Hadoop}
\item \textbf{Languages}	English: professional proficiency.  Russian: native
\end{itemize}
 
\section{Programming Experience}

\cvsubsection{T-Bank}[Moscow]
[ML engineer][Nov 2024 to present]

\begin{itemize}
\item Developed and deployed to production the NLP service FLAI (First Line AI) based on BERT for automatic classification of customer requests in T-Business. Backend: FastAPI, PostgreSQL, Kubernetes, CI/CD on GitLab. Implemented a full DevOps pipeline with monitoring and alerting. The service reduced support workload, freeing up 4 FTE support engineers.

\end{itemize}

\cvsubsection{S8 Capital}[Moscow]
[ML engineer][Mar 2023 to Oct 2024]

\begin{itemize}
\item Development of an \href{https://youtu.be/Esttc9j1bYk?si=leUdyXXYVqEZJzZN&t=4032}{SKU-SKU ranking and matching system} for the product aggregator price.ru. Content generation using LLM.

\end{itemize}

\cvsubsection{OzForensics}[Almaty]
[ML engineer][Dec 2021 to Mar 2023]

\begin{itemize}
\item Developed Quality Assessment models for a facial recognition system and anti-spoofing models. Built ML models for assessing eye openness and user smile levels (Ordinal Regression) and designed a neural network to protect against video stream spoofing.

\end{itemize}

\cvsubsection{Huawei Consumer Business Group}[Saint Petersburg]
[ML engineer][Dec 2020 to Dec 2021]

\begin{itemize}
\item Developed OCR in the wild, synthetic data generators, and preprocessing of poorly labeled data (structuring point clouds). Trained models and built an ML model for detecting highlights in basketball games (Temporal Shift Module).

\end{itemize}

\cvsubsection{Aktiv financial group}[Saint Petersburg]
[ML engineer][Oct 2019 to Dec 2020]

\begin{itemize}
\item Developed an OCR system for recognizing Russian passports from photos. Applied computer vision methods without neural networks, EasyOCR, Tesseract, synthetic data generators, and trained a custom OCR model.
\end{itemize}

\cvsubsection{GetLooky}[Saint Petersburg]
[Python programmer][Mar 2019 to Oct 2019]

\begin{itemize}
\item Developed a user question classification system using classic ML algorithms and word2vec.
\end{itemize}
 
\section{Teaching Experience }

\cvsubsection{Gostilitskaya school}[Saint Petersburg]
[Mathematics teacher][Sep 2018 to Aug 2019]

\begin{itemize}
\item Taught 10–11 grade students. All of my students scored above the regional average. One student scored 90 on the Unified State Exam in Mathematics. Successfully prepared two medal-winning graduates.
\end{itemize}

\cvsubsection{Physics and Mathematics teacher}
[Private teacher][Sep 2013 to present]

\begin{itemize}
\item Authored a proprietary curriculum for preparing students for the Unified State Exam in Mathematics and Physics. My students were admitted to top universities such as St. Petersburg State University, Moscow State University, Bauman Moscow State Technical University, and Ural Federal University.
\end{itemize}

\section{Science Experience }

\cvsubsection{SPbSU Solid State Laboratory}[Saint Petersburg]
[Research engineer][Nov 2016 to Jan 2017]

\begin{itemize}
\item Studied the structural integrity and optical properties of nanowires, closely related to the topic of my thesis. Participated in the growth of GaN crystals on silicon and sapphire substrates. Took part in a \href{https://pureportal.spbu.ru/en/projects/modeling-of-formation-of-iiiv-nanowirebased-heterostructures-for-information-technologies-and-high-performance-computing(3d53fa04-1848-44ed-866c-2e067cc45b28).html}{grant-funded research project}.
\end{itemize}

\section{Education}

\begin{itemize}
\item Bachelor, Solid State Physics Department, Saint Petersburg State University, 2017  
\end{itemize}

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
