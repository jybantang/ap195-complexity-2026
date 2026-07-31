# Machine Problem 0: Exploration
[Main](../README.md) | [Next](./)

## OBJECTIVE: Successfully Explore Julia
Provide a Google Docs documentation for the following Key Results (KR).
Use the provided template.
You may need a screenshot / printscreen to provide evidence on the following.
- [ ] **KR1:** Confirmed installation of both [Julia](https://julialang.org/downloads/) and [VSCode](https://code.visualstudio.com).
      The VSCode instance should be able to recognize Julia by installing the following extensions within VSCode.
      - `Julia: Julia Language Support`
      - `Julia Color Themes: Color themes for the Julia language`
- [ ] **KR1a:** Created dedicated folder for AP195 Machine Problems.
      The structure of the folder must follow as instructed below.
      Run Julia REPL in the command line interface (CLI) and issue the `versioninfo()` command in the installed Julia REPL environment to show the relevant information of the installation.
- [ ] **KR1a:** 
- [ ] **KR2a:** Successful execution of [mathematical commands via the Julia terminal ("advanced" calculator function) following a tutorial page](https://en.wikibooks.org/wiki/Introducing_Julia/The_REPL#Julia_and_mathematics) ...
- [ ] **KR2b:** ... up to generating a histogram of a normal-distributed (Gaussian) random numbers.
- [ ] **KR3:** Show switching of REPL to [the four REPL modes](https://en.wikibooks.org/wiki/Introducing_Julia/The_REPL). Discuss the differences and use of each mode.
- [ ] **KR4:** Display the type hierarchy in Julia (starting from `Number`) similar to one shown in [the Julia Documentation page](https://docs.julialang.org/en/v1/base/numbers/). Utize the [`showtypetree()` function in the wikibooks page](https://en.wikibooks.org/wiki/Introducing_Julia/Types).

# Folder structure
The folder structure should follow the structure of this repository.
Avoid the use of space character for filenames and folder names. Use dash `-` instead.
```
[path-to-folder]/ap195-complexity-2026-[surname]/
```
The `[path-to-folder]` indicates the local folder where you wish to place your ap195 machine problem files.
The `[surname]` should be your own surname (e.g. `delacruz`, without the spaces, lowercase).

# Installing Julia
Julia app can be directly downloaded from the Julialang.org [“Download Julia” page](https://julialang.org/downloads). 
This will provide CLI Julia.
I recommend downloading the latest stable (25 December 2023), **v 1.10.0** via terminal command in that page.
Installing the `juliaup` is the latest best way.
I have tried [installing Julia via `brew`](https://formulae.brew.sh/formula/julia) (I work with MacOS), but recently the version is delayed (v.1.9.4) and reverted to the CLI and `juliaup`.
You may still opt to use the `brew` and the delayed Julia version should not be a problem.

# Julia tutorials
Based on experience, one only needs to go through the Julia codes directly and only refer to documentation **as need arises**.
Our aim is to utilize numerical methods to learn Physics, not to become programming experts.
For the most part, experience is the best teacher for programming.

We wish to become physicists who can use the computer to help us in our scientific quest.
- [Julia Documentation](https://docs.julialang.org/en/v1/)
- [Start using Julia](https://docs.julialang.org/en/v1/manual/getting-started/)
- [Plots Basics](https://docs.juliaplots.org/latest/basics/)
- [Plots Tutorial](https://docs.juliaplots.org/latest/tutorial/)
- [Pkg Basics](https://pkgdocs.julialang.org/v1/getting-started/#Basic-Usage)

# Installing Jupyter notebook
**Jupyter Notebooks** are fun to use.
Notebooks can contain discussions like a diary.
PDF files as part of reports may be [generated directly](https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_export-your-jupyter-notebook) from Jupyter notebooks.

Since we will eventually use this as a way to submit your machine problem solutions, here are the relevant links.
- Main [Jupyter page](https://jupyter.org).
- Jupyter Notebook documentation is found [online](https://jupyter-notebook.readthedocs.io/en/stable/).
- Jupyter Notebook installation will require Python installation via [Anaconda](https://www.anaconda.com/products/distribution).
- Installing IJulia and Julia kernel into Jupyter is found in the [IJulia documentation](https://julialang.github.io/IJulia.jl/stable/).

Installation of Jupyter notebook allows beautiful notebooks, .ipynb, that can me exported (via "download") to PDF or HTML formats.

# Installing Julia extension in VSCode
VSCode is becoming popular in many programming languages.
One feature is its ability to incorporate many formatting schemes.
[There is a Julia an extension](https://code.visualstudio.com/docs/languages/julia) in your existing [VSCode installation](https://code.visualstudio.com/download).
VSCode also provides direct access to the appropriate terminal within your own OS.
GitHub scripts extension is also available, an advantage for coding teamwork.

VSCode can be used in to edit either: raw .jl file, or .ipynb file.
VSCode also provides direct access to the appropriate terminal within your own OS.
GitHub scripts extension is also available, an advantage for coding teamwork.

VSCode can be used in to edit either: raw .jl file, or .ipynb file.
