# TeXbook  Jupyter Notebook Theme

**Note**: You just hit the `custom-css `branch where the **full-fledged** Jupyter Custom theme is available and maintained.

## Prologue:  <img src="https://render.githubusercontent.com/render/math?math=%5Ctextbf%7B%5CTeX%5Ctext%7Bbook%7D%7D">  shall be _thy_ name

When I designed this theme, I was aiming towards a notebook experience which had the elegance and sobriety of a `LaTeX`-generated article, perfectly combined with the flexibility and interactivity of Jupyter notebooks.
And so <img src="https://render.githubusercontent.com/render/math?math=%5CTeX%5Ctext%7Bbook%7D"> seemed to be the most obvious solution for a name, a unique [portmanteau](https://www.merriam-webster.com/dictionary/portmanteau)
[(1)]( "Pronunciation"),
blending together the words <img src="https://render.githubusercontent.com/render/math?math=%5CLaTeX"> and *note**book** *. 
*Incidentally*, this is also the name of the 
[Donald E. Knuth](https://en.wikipedia.org/wiki/Donald_Knuth)'s [book](http://www.ctex.org/documents/shredder/src/texbook.pdf) on `TeX`.

That was the omen.. 🤩

> Right!, One!... Two!... Five! [(2)]("Monty Python and the Holy Grail")

The <img src="https://render.githubusercontent.com/render/math?math=%5CTeX%5Ctext%7Bbook%7D"> Jupyter notebook theme wishes to pay a tribute of gratitude (in the name, and in the content) to two of the technologies I do use the most as researcher and data scientist.

---
`[(1)]` : `port·​man·​teau | \ pȯrt-ˈman-(ˌ)tō` <br />
`[(2)]`: [The Holy Hand Grenade](https://www.youtube.com/watch?v=xOrgLj9lOwk) - Monty Python and the Holy Grail
    

#### `TeXbook` Jupyter theme in a Nutshell

- *Computer Modern* fonts for Markdown typesetting;
	- *Computer Modern Typesetting* for Markdown Mono	
- `Fira Code` (_open source_) font as the default `monospace` for the **Code** editor (with ligatures support);
- `Hack` (_open source_) font as the default `monospace` font for **Markdown** editor (slightly better for text writing, _ed._);
- `md` and `code` colour highlight editor themes based on Material Design colour scheme.
    - other themes also provided;
    - very easy to create your own custom theme (just a series of CSS variables should do the trick)
- Special formatting for `pandas.DataFrame`
- Extra `ad-hoc` CSS classes for Markdown and Code (*output*) formatting

**Last but not least**: to make things even more interesting, the `TeXbook` theme has been made available in three different flavours: 

   	1. **Full-fledged** _custom_ Jupyter notebook theme;
 	2. `pip-installable` Custom **IPython magic** (`%texify`);
 	3. Custom theme integration for Google Colaboratory Notebooks (via the [Stylus](https://en.wikipedia.org/wiki/Stylus_(browser_extension)) browser extension) (**still experimental**).

### Sneak Peek?

Here is a [**Preview**](https://leriomaggio.github.io/texbook-jupyter-theme/) of how the theme looks like!

---

## How to 

Installing and Enabling the `TeXbook` theme for your Jupyter notebooks varies depending on which of the three theme settings you decided to use. 

1. [Jupyter Notebook Custom Theme](#custom)
2. [Custom IPython Magic](#magic)
3. [Google Colaboratory Theme](#colab)

<a name="custom"></a>
### Using `TeXbook` as default Jupyter Notebook theme

The `TeXbook` theme is available as a **full-fledged** `custom.css` that can be setup as the default theme for Jupyter notebooks.

Installing and enabling the `TeXbook` theme as the **default** Jupyter Notebook theme, it is 
very simple! Just copy the entire `custom` folder contained in this repository *as-is* in the 
`JUPYTER_CONFIG_DIR` folder (default `$HOME/.jupyter`).
See [here](https://jupyter.readthedocs.io/en/latest/use/jupyter-directories.html#configuration-files)) for more information.

<a name="magic"></a>
### Using `%texify` custom IPython magic

Instructions on how to install and enable the `%texify` Jupyter Notebook Extension 
are available [HERE](https://github.com/leriomaggio/texbook-jupyter-theme/blob/notebook-magic/README.md#magic)


<a name="colab"></a>
### `TexBook` theme for Google Colaboratory

**AVAILABLE SOON**   





