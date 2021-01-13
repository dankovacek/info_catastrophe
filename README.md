# Demo Repo for Jupyter Book and Binder

Launch the main Info Catastrophe notebok using Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dankovacek/info_catastrophe/info_catastrophe_presentation/info_catastrophe_nb.ipynb)


Info for [building books and hosting on Github Pages](https://jupyterbook.org/publish/gh-pages.html)

After updating any content, rebuilt the repo:

`jupyter-book build content/`

Then, update the github pages site. Use the gh-pages branch update tool:

`ghp-import -n -p -f _build/html`