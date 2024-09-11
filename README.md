## Nützliche Makros

### Standard frame
Befehl: ``\qframe``

Einfügen: 
```
\begin{frame}[t]{Title} \vspace{20pt}

\end{frame}
```

### Itemize frame
Befehl: ``\qiframe``
Einfügen:
```
\begin{frame}[t]{Title} \vspace{20pt}
	\begin{itemize}
		\item
	\end{itemize}
\end{frame}
```

### 2 Columns frame
Befehl: ``\2cframe``
Einfügen: 
```
	\begin{frame}[t]{Zwei Spalten} \vspace{20pt}
		\begin{columns}[T, onlytextwidth]
			\begin{column}{0.5\textwidth}
				Test
			\end{column}
			
			\begin{column}{0.5\textwidth}
				Test
			\end{column}
		\end{columns}
	\end{frame}
```
