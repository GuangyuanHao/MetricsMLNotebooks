# Applied Causal ML Notebooks

If you are facing difficulties running a notebook on your environment, try installing the packages in the requirements.txt file of the repo.

```bash
pip install -r requirements.txt
```


# For Contributors

The .Rmd files are auto-generated by a Github Action, whenever one pushes a .irnb (R Jupyter notebook) to one of the main folders of the repo on the main branch. So .Rmd files, should never be altered directly. Only changes to .irnb files should be made. Any change to a .Rmd file will be over-written by the corresponding .irnb file and will not survive the Github Action.

Moreover, whenever a push happens to the main branch, all python and R notebooks and all R Markdown files are stripped from their outputs. It is advisable that you always strip the notebooks before pushing to the repo. You can use `nbstripout --install` on your local git directory, which does this automatically for you. 