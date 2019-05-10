# Modern Physics Concise Review
## Instructions
### Step 0
Learn LaTeX and choose an editor (Overleaf, TexStudio). Install LaTeX if needed.
### Step 1
Create a folder for the concise review, if you're using an online editor make a new blank project. Download the `main.tex` file and move it to the folder (or upload it to the online editor).
### Step 2
Compile and View the `main.tex` file. You should see a title page.
### Step 3
Now in the same folder (or project) create a file using the following format `chapter00.tex`. Obviously replace the numbers with the relevant chapter number from the book. For example, for chapter 2 the title would be `chapter02.tex`. Your chapter files HAVE to be in the same folder as the `main.tex` file.
### Step 3.5
Go to the `main.tex` file and uncomment the line at the bottom for your chapter number. For example, for chapter 2 I would go down to the bottom and make this change. ONLY uncomment the lines for the chapters you have. 
```
\tableofcontents

% Chapters - EDIT THIS TO VIEW YOUR FILE
% Uncomment the line and name your file to compile

%\input{chapter01.tex}
\input{chapter02.tex}
%\input{chapter03.tex}
%\input{chapter04.tex}
%\input{chapter05.tex}
%\input{chapter06.tex}
%\input{chapter07.tex}
%\input{chapter08.tex}
%\input{chapter09.tex}
%\input{chapter10.tex}
%\input{chapter11.tex}
%\input{chapter12.tex}
%\input{chapter13.tex}
%\input{chapter14.tex}
%\input{chapter15.tex}
%\input{chapter16.tex}
%\input{chapter17.tex}
%\input{chapter18.tex}
   	
\end{document}
```
### Step 4
Begin your `chapter00.tex` file with `\chapter{Chapter Title}`; After that you are free to use `\section` and `\subsection` command. Refer to the example file. Refer to the `chapter02.tex` file for details.
# Instructions for Git users
Please do not commit and push your `main.tex` file or any other files. The only file that you may commit is your chapter files. Collaborators are allowed to commit so just be careful. Raise issues and we can try and fix it. 
# Known Issues
After you compile if you see Chapter 1 as the title that is okay. This happens because locally you may only have one chapter. But once we compile all our files together at the end, the numbering will sort itself out. 
