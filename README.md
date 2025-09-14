# Example
This section can be used between the content and bibliography comment to learn the most commonly used LaTeX tags.

    \section{section}
    content
    \subsection{subsection}
    This is a cite \cite{W4ppler}
    \subsubsection{subsubsection}
    Reference to the python code: \cref{python_code}

    \paragraph{codeblocks}

    \begin{lstlisting}[language=Python, caption=Python example, label=python_code,] 
    print("Hello World")
    \end{lstlisting}

    \paragraph{paragraph}
    this is a reference to a figure (Abb. \ref{fig:demo-figure})

    \begin{figure}[h]
        \centering
        \includegraphics[width=1cm]{LogoITHTL_white.png}
        \caption{this is a figure}
        \label{fig:demo-figure}
    \end{figure}
