# quarto-jupyter-sandbox

## Install quarto

```sh
pip install quarto
```

## Plain Text Editing

<https://quarto.org/docs/tools/jupyter-lab.html#plain-text-editing>

- execute all cells and render qmd to md/ipynb/html defined in qmd's YAML header

    ```yaml
    format:
      html:
        code-fold: false
      gfm:
        code-fold: false
      ipynb:
        code-fold: false
    ```

    ```sh
    quarto render basics-jupyter.qmd --execute
    ```

- just convert qmd to ipynb and vice versa

    ```sh
    quarto convert basics-jupyter.qmd   # converts to ipynb
    quarto convert basics-jupyter.ipynb # converts to qmd
    ```
