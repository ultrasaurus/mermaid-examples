# mermaid-examples

Experiment using mermaid with hugo

Deployed here for now: https://sharp-curran-7b3006.netlify.com/








## hugo setup

```
hugo new site mermaid-examples
git submodule add https://github.com/matcornic/hugo-theme-learn.git themes/learn
```


create some pages
```
hugo new --kind chapter basics/_index.md
hugo new basics/first-content.md
hugo new basics/second-content/_index.md
```