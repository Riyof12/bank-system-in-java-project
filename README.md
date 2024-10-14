\documentclass[a4paper,12pt]{report} % Document class set to 'report' with A4 paper and 12pt font size
\usepackage{graphicx} % For including images
\usepackage{hyperref} % For clickable links in the table of contents
\usepackage{tocloft}  % To customize the table of contents, figures, and tables
\usepackage{longtable} % For long tables
\usepackage{listings}  % For formatting and displaying code listings
\usepackage{amsmath}   % For mathematical symbols if needed

% Title Page Information
\title{\textit{\textbf{Banking System in Java Project}}} % Title of the project
\author{\textbf{\textit{Team by: Jood - Rood -
Rania  - Riyouf Alshaikh}}} % Author of the document
\begin{document}

% Cover Page
\maketitle % This command creates the title page based on the title, author, and date

% Table of Contents
\tableofcontents % Automatically generates the table of contents
\newpage % Adds a new page after the table of contents

% Table of Figures
\listoffigures % Automatically generates the list of figures
\newpage % Adds a new page after the list of figures

% Table of Tables
\listoftables % Automatically generates the list of tables
\newpage % Adds a new page after the list of tables

% Introduction
\chapter{Introduction} % First chapter, labeled as "Introduction"
The \textbf{Banking System in Java Project} is a software designed to simulate banking operations such as creating accounts, managing deposits and withdrawals, and viewing account balances. The main purpose of this software is to automate banking processes and provide users with an easy way to manage their financial accounts. Key features include secure login, multi-account management, and transaction tracking.

\newpage % Forces a page break to start the next section on a new page

% Installation and Configuration
\chapter{Installation and Configuration} % Second chapter, labeled as "Installation and Configuration"
To install and configure the \textit{Banking System in Java}, follow these steps:

\section{System Requirements} % Section for system requirements
\begin{itemize}
    \item Java JDK version 8 or above % List item for Java requirement
    \item A Java IDE (e.g., Eclipse, IntelliJ IDEA) % List item for Java IDE
    \item Minimum 2 GB RAM, 500 MB free disk space % List item for system resources
\end{itemize}

\section{Installation Steps} % Section for installation steps
\begin{enumerate}
    \item Download the project files from the repository. % Step 1: Download
    \item Import the project into your Java IDE. % Step 2: Import
    \item Set up the database (if applicable) by following the provided SQL scripts. % Step 3: Database setup
    \item Run the project from the IDE. % Step 4: Run the project
\end{enumerate}

\section{Configuration} % Section for configuration
If the project requires any special configuration (e.g., database connection settings), modify the configuration file located in the \texttt{config} directory. % Description of configuration steps

\newpage

% User Guide
\chapter{User Guide} % Third chapter, labeled as "User Guide"
\section{Creating an Account} % Section on account creation
To create a new account, follow these steps:
\begin{enumerate}
    \item Launch the program. % Step 1: Launch
    \item Click on "Create Account". % Step 2: Click on "Create Account"
    \item Fill in the required fields: name, account number, and PIN. % Step 3: Fill in fields
    \item Click "Submit". % Step 4: Submit
\end{enumerate}

% Example of how to include an image with caption and reference
\begin{figure}[h] 
    \centering
    \includegraphics[width=0.7\textwidth]{account_creation.png} % Example image file
    \caption{Account Creation Screen} % Figure caption
    \label{fig:account_creation} % Label for referencing in the text
\end{figure}

\section{Managing Accounts} % Section on account management
After logging in, you can: 
\begin{itemize}
    \item \textbf{Deposit Money}: Select the account and enter the amount. % Feature 1: Deposit
    \item \textbf{Withdraw Money}: Ensure sufficient balance before making a withdrawal. % Feature 2: Withdraw \item \textbf{Check Balance}: View your current balance for any account. % Feature 3: Check balance
\end{itemize}

\newpage

% Troubleshooting and Support
\chapter{Troubleshooting and Support} % Fourth chapter, labeled as "Troubleshooting and Support"
\section{Common Issues} % Section on common issues users might face
\begin{itemize}
    \item \textbf{Issue: Unable to log in.} % Example issue
    \newline
    \textbf{Solution:} Ensure that you are entering the correct account number and PIN. % Solution to the issue
    \item \textbf{Issue: Account balance not updating.} % Another example issue
    \newline
    \textbf{Solution:} Refresh the account page or restart the application. % Solution to the issue
\end{itemize}

\section{Support Contact} % Section for support contact information
For further assistance, please contact support at \texttt{support@bankingsystem.com}. % Example email for support

\newpage

% Glossary
\chapter{Glossary} % Fifth chapter, labeled as "Glossary"
\begin{itemize}
    \item \textbf{API}: Application Programming Interface. % Glossary term 1
    \item \textbf{IDE}: Integrated Development Environment. % Glossary term 2
    \item \textbf{JDK}: Java Development Kit. % Glossary term 3
    \item \textbf{PIN}: Personal Identification Number. % Glossary term 4
\end{itemize}

\newpage

% Licensing and Legal Information
\chapter{Licensing and Legal Information} % Sixth chapter, labeled as "Licensing and Legal Information"
The \textit{Banking System in Java} is licensed under the MIT License. You are free to use, modify, and distribute the software under the following conditions: % Explanation of licensing
\begin{itemize}
    \item Attribution must be given to the original authors. % License condition 1
    \item No liability is assumed by the authors for any damage caused by using this software. % License condition 2
\end{itemize}

For full licensing terms, visit \url{https://www.example.com/licenses}. % Link to licensing terms

\vfill
\begin{center}
    \textbf{Copyright © 2024 Banking System in Java. All rights reserved.} % Copyright information
\end{center}

\end{document}
