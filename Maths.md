# Maths in GitHub markdown files
GitHub uses [Mathjax](https://www.mathjax.org/) to render common $\LaTeX$ notation. There are lots of cheatsheets for this notation that you'll find with a quick search. If you can translate a formula into Excel, you'll have no problem getting the hang of Mathjax.

Unlike Mathcad, this only presents formulas. It doesn't solve them.

Mathematical notation is often a much clearer way to explain how formulas in your scripts work compared to inline code. It can also make the theory you have used instantly recognisable to others.

For example,
```
When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are: 
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$
```
Is rendered as:

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are: 
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$  

This feature was only [added in May 2022!](https://github.blog/2022-05-19-math-support-in-markdown/)
