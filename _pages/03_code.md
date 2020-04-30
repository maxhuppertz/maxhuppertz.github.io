---
layout: page
title: Code
permalink: /code/
---

## Post-selection inference in Python
I wrote a Python port, [available on GitHub][hdmpy_github]{:target="_blank"}, of parts of the excellent [R package hdm][hdm_cran]{:target="_blank"} by Victor Chernozhukov, Chris Hansen, and Martin Spindler. None of the theory or the original code are mine; all credit goes to the authors. All I did was port parts of it into Python and enable parallel processing. This makes the Python port much faster than the original R package for anything which involves simulations, for example data dependent penalty terms for robust LASSO.

## Linear models in Python
I wrote a Python package, [available on GitHub][lmpy_github]{:target="_blank"}, to run linear models in Python. It is in many ways similar to (and will often miss functionality provided by) existing packages, such as [statsmodels][statsmodels]{:target="_blank"} or [scikit-learn's linear regression][sklearn_linear_regression]{:target="_blank"}, but contains some additional capabilites, such as clustered standard errors and some bootstrap algorithms (e.g. the wild bootstrap with the ability to impose the null, and the cluster robust bootstrap from [Cameron, Gelbach, and Miller, 2008][cgm_paper]{:target="_blank"}). It also contains the ability to drop variables based on their variance inflation factors, mostly to mirror functionality provided by STATA.

## Misc
I have a [GitHub repo][grad_code_github]{:target="_blank"} containing code I wrote for various grad school classes.

[cgm_paper]: https://www.mitpressjournals.org/doi/10.1162/rest.90.3.414
[grad_code_github]: https://github.com/maxhuppertz/grad_school_code
[hdmpy_github]: https://github.com/maxhuppertz/hdmpy
[hdm_cran]: https://cran.r-project.org/web/packages/hdm/index.html
[lmpy_github]: https://github.com/maxhuppertz/lmpy
[sklearn_linear_regression]: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
[statsmodels]: https://www.statsmodels.org/stable/index.html
