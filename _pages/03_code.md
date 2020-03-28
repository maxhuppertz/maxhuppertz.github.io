---
layout: page
title: Code
permalink: /code/
---

## Post-selection inference
I wrote a Python port, [available on GitHub][hdmpy_github]{:target="_blank"}, of parts of the excellent [R package hdm][hdm_cran]{:target="_blank"} by Victor Chernozhukov, Chris Hansen, and Martin Spindler. None of the theory or the original code are mine; all credit goes to the authors. All I did was port parts of it into Python and enable parallel processing. This makes the Python port much faster than the original R package for anything which involves simulations, for example data dependent penalty terms for robust LASSO.

## Misc
I have a [GitHub repo][grad_code_github] containing code I wrote for various grad school classes.

[hdmpy_github]: https://github.com/maxhuppertz/hdmpy
[hdm_cran]: https://cran.r-project.org/web/packages/hdm/index.html
[grad_code_github]: https://github.com/maxhuppertz/grad_school_code
