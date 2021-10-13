---
layout: default
title: Home
nav_order: 1
---

## Home

**People.** The first principle in the lab is people. Projects occur because people think and work on them. Share here some basic information about the team involved in the project. Use hyperlinks as needed. Add a picture of you or the team. Introduce yourself and any bio that you consider relevant. Mention the other members involved. Here is an example. Welcome to the documentation of the [project_template](https://github.com/luquelab/project_template/tree/main/docs) GitHub repository! My name is Antoni Luque, and I am leading this project. I'm an Associated Professor in the [Mathematics & Statistics Department](https://math.sdsu.edu) at San Diego State University ([SDSU](https://www.sdsu.edu)) If you have any questions you can contact me at my SDSU email: [aluque@sdsu.edu].

** What.** This project is a template for projects in my [lab](https://www.luquelab.com).

** Why.** Research projects usually get shaped to be published in articles. This project template is part of an initiative to make research more accessible to the general and specialized public, from the beginning of a project.

** How.** The documentation is generated using Jekyll and GitHub Pages from the docs/ folder in the GitHub repo associated with the project. The updates in the documentation are reflected in the repository.

** What else? ** Use the side panel to learn more about the current project's [Synthesis](/docs/synthesis/index.md), [Approach](), [Outputs](), and [Impact](). Check also our [Athena initiative](https://luquelab.github.io/Athena/knowledge/synthesis.html). 

---

## Technical information on how to organize the documentation
The associated file `index.md` contains a YAML front matter to indicate the layout, title, and navigation options. The repo's website is based on Jekyll's theme [Just-the-Docs](https://pmarsceill.github.io/just-the-docs/). Explore their [documentation]([Just-the-Docs](https://pmarsceill.github.io/just-the-docs/)) and associated [GitHub repo](https://github.com/pmarsceill/just-the-docs) to adapt your project's website to your needs.
---

The `head.html` file from the original template has been modified in `/docs/_includes` to include MathJax, so you can write math using latex format. Here are some examples:

Math equation using MathJax: $$5+5$$

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

\( 5+5 \)

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are
\begin{equation}
  x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
\end{equation}

May Athena be with you.
