To use this theme, copy the `custom.css` file to `~/.jupyter/custom/custom.css`

More precisely:
```bash
cd ~/.jupyter
mkdir custom  # may already exist
cd .jupyter/custom
rm custom.css
wget https://raw.githubusercontent.com/rsomani95/jupyter-custom-theme/master/custom.css
```

Until a more elegant solution is in place, to apply the matplotlib theme,  you'll need to inject all the code from `matplotlib.py` into your local environment
