**Why**: Run code interactively, with diagrams, text and visualizations on *indivdiual* ***cells***.

**How**: Succeeded from the [Ipython](https://ipython.org/) project.

**What**:

###### Installation
1. If you have Python3 installed skip this, Install [Anaconda](https://anaconda.org/).
2. Install Jupyter Notebook, using pip. ``pip install notebook``
3. Run in terminal, ``jupyter notebook``.
4. Ignore the terminal and follow from the automatically opened browser.

###### There are two modes:
- *Command* mode: control cells
- *Edit* mode: edit cell content

---
###### Content is of two type:
- Code
- Markdown
Switch using the top bar.
---
All functions are available on top bar.

###### Some shortcut keys for functions:
- Command mode: <kbd>Esc</kbd>

- Edit mode: <kbd>Enter</kbd> on the selected cell

- Execute cell: <kbd>Ctrl</kbd> + <kbd>Enter</kbd>

---
###### Cell execution order is shows on cells in square brackets.
So, **cell order is not necessarily the execution order.**

---
###### Cell and line *magic*s
- These are special commands activated using one or two (percent - **%**) sign.
- Use `%lsmagic` to see all the magic commands.
- Some cell and line magic commands:
	- `%%html` - add an iframe and have fun!
	- `%ls`
	- `%%javascript`
	- `%%bash`
	- `%%timeit` (add this as the first line and see the runtime before the output)
---
###### You can use asterisk (!) to add bash commands like `ls, cat, nano`
---
###### Exporting the notebook
The notebook can be downloaded as:
- Python
- HTML
- LaTeX
- PDF via HTML, LaTeX
- Notebook (`.ipynb`)

### Useful for exploring data, computing in general and for visualization!
