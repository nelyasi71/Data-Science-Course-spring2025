\documentclass[11pt]{article}

\usepackage[a4paper,margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{setspace}
\usepackage{titlesec}
\usepackage{enumitem}

\hypersetup{
    colorlinks=true,
    linkcolor=blue,
    urlcolor=blue,
    pdftitle={Data Science Course – Spring 2025},
    pdfauthor={Data Science Course Students}
}

\title{\textbf{Data Science Course -- Spring 2025}}
\author{}
\date{}

\begin{document}
\maketitle
\vspace{-1em}

\onehalfspacing

\section*{Overview}
This repository contains coursework, assignments, and the final project for the
\textbf{Data Science Course (Spring 2025)}.
The material covers the complete data science pipeline, including probability,
statistics, data analysis, machine learning, deep learning, natural language processing,
data engineering, and end-to-end project development.

\section*{Repository Structure}

\begin{itemize}[leftmargin=2em]
    \item \hyperref[ca0]{CA-0: Probability \& Statistics}
    \item \hyperref[ca1]{CA-1: Data Analysis \& Visualization}
    \item \hyperref[ca2]{CA-2: Data Engineering \& Streaming}
    \item \hyperref[ca3]{CA-3: Classical Machine Learning}
    \item \hyperref[ca4]{CA-4: Neural Networks \& Deep Learning}
    \item \hyperref[ca56]{CA-5 \& CA-6: NLP, Information Retrieval \& Computer Vision}
    \item \hyperref[mainproject]{Main Project: End-to-End Language Modeling}
\end{itemize}

\newpage

% ============================
\section*{Course Assignments}

\subsection*{\label{ca0}CA-0: Probability \& Statistics}
\textbf{Folder:} \texttt{CA-0}

\begin{itemize}
    \item Monte Carlo simulations
    \item Probability distributions and expectations
    \item Confidence intervals and hypothesis testing
    \item Statistical analysis on real-world datasets
\end{itemize}

\textbf{Tools:} NumPy, Pandas, SciPy, Matplotlib

\bigskip

\subsection*{\label{ca1}CA-1: Data Analysis \& Visualization}
\textbf{Folder:} \texttt{CA-1}

\begin{itemize}
    \item Exploratory data analysis on Airbnb datasets
    \item Geographical and statistical insights
    \item Visual analytics and reporting
\end{itemize}

\textbf{Tools:} Pandas, Matplotlib, Tableau, Excel

\bigskip

\subsection*{\label{ca2}CA-2: Data Engineering \& Streaming}
\textbf{Folder:} \texttt{CA-2}

\begin{itemize}
    \item Streaming data pipelines
    \item Kafka-based consumers and producers
    \item Containerized environments with Docker
\end{itemize}

\textbf{Tools:} Kafka, Docker, PySpark, MongoDB

\bigskip

\subsection*{\label{ca3}CA-3: Classical Machine Learning}
\textbf{Folder:} \texttt{CA-3}

\begin{itemize}
    \item Classification and regression tasks
    \item Feature engineering and model evaluation
    \item Recommender systems
\end{itemize}

\textbf{Applications:}
\begin{itemize}
    \item Cancer prediction
    \item Bike rental prediction
    \item Recommendation systems
\end{itemize}

\textbf{Tools:} Scikit-learn, XGBoost

\bigskip

\subsection*{\label{ca4}CA-4: Neural Networks \& Deep Learning}
\textbf{Folder:} \texttt{CA-4}

\begin{itemize}
    \item Feedforward neural networks
    \item Match outcome prediction
    \item Model evaluation and comparison
    \item Convolutional neural network theory (bonus)
\end{itemize}

\textbf{Tools:} PyTorch, TensorFlow/Keras

\bigskip

\subsection*{\label{ca56}CA-5 \& CA-6: NLP, Information Retrieval \& Computer Vision}
\textbf{Folder:} \texttt{CA-5-6}

\begin{itemize}
    \item Text preprocessing and vectorization
    \item Full-text search vs semantic search
    \item Transformer-based NLP models
    \item Image processing and segmentation
\end{itemize}

\textbf{Tools:} NLTK, Gensim, HuggingFace Transformers, OpenCV

\newpage

% ============================
\section*{\label{mainproject}Main Project: End-to-End Language Modeling}

The main project is a multi-phase data science project focused on
\textbf{text analysis and language modeling}, developed as an end-to-end pipeline.

\subsection*{Phase 1: Text Analysis \& Feature Engineering}
\begin{itemize}
    \item Text preprocessing and tokenization
    \item Word, n-gram, and sentence statistics
    \item Exploratory analysis and visualization
\end{itemize}

\subsection*{Phase 2: Data Management}
\begin{itemize}
    \item Dataset construction
    \item Structured storage using CSV and SQLite
\end{itemize}

\subsection*{Phase 3: Modeling \& Training}
\begin{itemize}
    \item LSTM and Transformer models
    \item Pretrained model fine-tuning
    \item Experiment tracking with MLflow
\end{itemize}

\subsection*{Pipeline \& Automation}
\begin{itemize}
    \item Modular preprocessing and training scripts
    \item Reproducible experiment setup
    \item Continuous integration with GitHub Actions
\end{itemize}

% ============================
\section*{Notes}
\begin{itemize}
    \item Some folders contain alternate or backup notebook versions.
    \item Generated datasets and intermediate outputs are included for reproducibility.
    \item This repository is intended for academic and educational use.
\end{itemize}

\section*{Authors}
Students of the \textbf{Data Science Course -- Spring 2025}

\end{document}
