# Syntax is simple!
### In 5 lines

1. `/section{ sectionName }` to create a new section and the text follows are part of this section
2. `/subsection{ subsectionName }` to create subsection within section and the text follows are part of this subsection
3. `/ref{ Journal/Book/... }` to cite references and its isolated and the text follows donot considered as part of this tag
4. `/media{ Image/GIF/ShortVid }` upload media files within the curly braces to included
5. Example Illustrates better so take a look here

```
Lorem Ipsum is simply dummy text of the printing and ... Lorem Ipsum. \ref{https://www.lipsum.com/}

\section{History}

Contrary to popular belief, ... 2000 years old. 

\subsection{More clear}

Richard McClintock, a Latin ... written in 45 BC. 

\subsection{Book}
This book is a treatise on the theory of \ref{editoriam references} ethics, ... \ref{www.nature.com} \ref{remains}

\section{Uses}

It is a long established fact ... readable English. \ref{uses01} \ref{uses02}

Many desktop publishing packages ... , sometimes on purpose (injected humour and the like).\ref{again-uses2}
```

Output:
