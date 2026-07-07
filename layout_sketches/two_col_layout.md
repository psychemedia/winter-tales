  two col / two column verse layout

Layout
https://ctan.org/pkg/reledpar and https://ctan.org/pkg/reledmac

---

\usepackage{reledmac}
\usepackage{reledpar}

\begin{pages}
\begin{Leftside}
\beginnumbering
\pstart
% Stanza 1...
\pend
\pstart
% Stanza 2...
\pend
% ... continue for 50 stanzas if needed ...
\endnumbering
\end{Leftside}

\begin{Rightside}
\beginnumbering
\pstart
% Translation 1...
\pend
\pstart
% Translation 2...
\pend
% ... matching translations ...
\endnumbering
\end{Rightside}
\end{pages}

\Pages  % Typesets everything, across multiple pages automatically

---



::: {.columns}
::: {.column width="48%"}
Left column content here
:::

::: {.column width="48%"}
Right column content here
:::
:::