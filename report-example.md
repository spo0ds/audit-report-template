---
title: Protocol Audit Report
author: YOUR_COMPANY_NAME_HERE
date: DATE_HERE
header-includes:
  - \usepackage{titling}
  - \usepackage{graphicx}
---

\begin{titlepage}
    \centering
    \begin{figure}[h]
        \centering
        \includegraphics[width=0.5\textwidth]{logo.pdf} 
    \end{figure}
    \vspace*{2cm}
    {\Huge\bfseries Protocol Audit Report\par}
    \vspace{1cm}
    {\Large Version 1.0\par}
    \vspace{2cm}
    {\Large\itshape COMPANY_WEBSITE_HERE\par}
    \vfill
    {\large \today\par}
\end{titlepage}

\maketitle

<!-- Your report starts here! -->

Prepared by: 

- Auditor's name
- Auditor's name

\newpage

# Table of Contents
- [Table of Contents](#table-of-contents)
- [Protocol Summary](#protocol-summary)
- [Disclaimer](#disclaimer)
- [Risk Classification](#risk-classification)
- [Audit Details](#audit-details)
  - [Scope](#scope)
- [Executive Summary](#executive-summary)
  - [Issues found](#issues-found)
- [Findings](#findings)
    - [\[S-#\] TITLE (Root + Impact)](#s--title-root--impact)

# Protocol Summary

Protocol does X, Y, Z

# Disclaimer

The YOUR_COMPANY_NAME_HERE team makes all effort to find as many vulnerabilities in the code in the given time period, but holds no responsibilities for the findings provided in this document. A security audit by the team is not an endorsement of the underlying business or product. The audit was time-boxed and the review of the code was solely on the security aspects of the Solidity implementation of the contracts.

# Risk Classification

|            |        | Impact |        |     |
| ---------- | ------ | ------ | ------ | --- |
|            |        | High   | Medium | Low |
|            | High   | H      | H/M    | M   |
| Likelihood | Medium | H/M    | M      | M/L |
|            | Low    | M      | M/L    | L   |

# Audit Details

## Scope 


- review commit hash - COMMIT_HASH_HERE

- [repo link](LINK_TO_THE_GITHUB_REPOSITORY)



# Executive Summary

Over a NUMBER_OF_DAYS_HERE-day period, PROTOCOL_NAME_HERE collaborated with us to review the PROTOCOL_FUNCTION_AUDITING_HERE protocol. During this time, a total of NUMBER_OF_ISSUES_HERE issues were identified. During this engagement we had as set of distinct goals focusing on a number of different components:

- MENTION_WHAT_WAS_YOUR_FOCUS_WHILE_AUDITING

## Issues found

<!-- \begin{center} -->
\begin{tabular}{ | m{5cm} | m{5cm}| }
\hline
\textbf{Severity} & \textbf{Amount} \\
\hline
High risk & NUMBER_HERE \\
\hline
Medium risk & NUMBER_HERE \\
\hline
Low risk & NUMBER_HERE \\
\hline
Informational & NUMBER_HERE \\
\hline
Total  & NUMBER_HERE \\
\hline
\end{tabular}
<!-- \end{center} -->

# Findings

### [S-#] TITLE (Root + Impact)

**Description**

**Proof of Concepts**

**Recommended mitigation**
