# Miscellaneous

---

## Latex tricks

* [Format is off on only some page numbers](https://github.com/tatpongkatanyukul/Courses/blob/main/misc/PageNumberFormatOff.zip)
  * Figure messes up the environment.
   * Fix:
     Add dummy paragraph environment
     ```
     \paragraph{}
     ```
  * ```\lstinputlisting``` goes across pages and messes up the format of page numbers.
    * Break it into smaller pieces such that no piece goes across pages.
    * Bring the code inside ```\begin{Exercise}```-```\end{Exercise}``` scope.
      
---
