# MP0: Set-up and exploration
[Main](../README.md) | [Next](./)

## 🎯 Objective
Establish and verify your local computational research environment (VS Code, Julia, Jupyter, Git) including a successful submission of requirements.

---

## 📊 Key Results (Your Grading Rubric)

### 😎 Basic KRs (≤ 80%)
- [ ] **KR1 (Julia and IDE):** 
  Confirmed installation of both [Julia](https://julialang.org/downloads/) and [VSCode](https://code.visualstudio.com) along with the required plugins.
  Run Julia REPL in the command line interface (CLI) and issue the `versioninfo()` command in the installed Julia REPL environment to show the relevant information of the installation.
  The VSCode instance should be able to recognize Julia by installing the following extensions within VSCode.      
    - Language support: `Julia: Julia Language Support`
    - Color theme: `Julia Color Themes: Color themes for the Julia language`
- [ ] **KR2 (Environment & Code Inheritance):** 
  Clone the starter template repository (see instructions below) and instantiate the isolated Julia environment (`Project.toml` via `Pkg.instantiate()`), and run the baseline notebook top-to-bottom without execution errors.
- [ ] **KR4 (Basic report):** Submitted two files: (1) PDF export as report of the jupyter file/s containing cells with outputs, and (2) file of the zipped folder containing the notebook and the codes (except the PDF) making sure that the appropriate cells have been updated with your personal metadata as required.

### 🫡 Outstanding KRs (up to +20%)
For students aspiring to demonstrate early computational mastery:

- [ ] **KR4 (Exploratory Parameter Shift):** 
  Create another notebook that extends the discrete logistic map trajectory sweep by adding a third control parameter regime ($r = 3.56$, the onset of period-doubling) and overlay it on the Cell 5 plot.
- [ ] **KR5 (Automated File Export Hygiene):** 
  Modify the figure saving logic in Cell 5 to automatically tag saved plot images with your student ID and timestamp (e.g., `figures/mp0_plot_202612345.png`) using Julia string interpolation.

## Installing Julia
Julia app can be directly downloaded from the Julialang.org [“Download Julia” page](https://julialang.org/downloads). 
This will provide CLI Julia.
I recommend downloading the latest stable version.
Installing the `juliaup` is the latest best way to ensure that your Julia installation is updated properly.

## Julia tutorials
Based on experience, one only needs to go through the Julia codes directly and only refer to documentation **as need arises**.
Our aim is to utilize numerical methods to learn Physics, not to become programming experts.
For the most part, experience is the best teacher for programming.
We wish to become physicists who can use the computer to help us in our scientific quest.

The best starting point for those with non-Julia background is found in [Manual >> Getting Started](https://docs.julialang.org/en/v1/manual/getting-started/).
The following documentation and tutorial links are best.
- [Julia Documentation](https://docs.julialang.org/en/v1/)
- [Start using Julia](https://docs.julialang.org/en/v1/manual/getting-started/)

## VSCode and VSCode extensions
VSCode is becoming popular IDE recently.
Make sure that [the latest version is installed in your OS](https://code.visualstudio.com/download).
One feature is its ability to incorporate many formatting schemes.
[There is a Julia an extension](https://code.visualstudio.com/docs/languages/julia) in your existing VSCode installation.

VSCode also provides direct access to the appropriate terminal within your own OS.
GitHub scripts extension is also available, an advantage for coding teamwork.
VSCode can be used in to edit either: raw `.jl` file, or `.ipynb` file.
The `.ipynb` file can also be exported to `.pdf` formats within the VS Code.
You may need to install appropriate extensions within VS Code for this.

VSCode also provides direct access to the appropriate terminal within your own OS.
GitHub scripts extension is also available, an advantage for coding teamwork.

## Jupyter inside VSCode
There is no need to install independent Jupyter installation.
Instead some extensions may be needed to be installed such as: 
`Jupyter`, `Julia Language Support`, `Julia Color Themes`.
Other recommended (no neecesary) extensions; `Markdown Julia`, `GitHub Pull Requests`.

We shall use Jupyter notebooks for your machine problem solutions documentations.
The documentation shall form part of your reports in pdf format.
PDF files as part of reports may be [generated directly](https://code.visualstudio.com/docs/datascience/jupyter-notebooks#_export-your-jupyter-notebook) from Jupyter notebooks.

## Independent repository clone
You may generate a new repository with the same directory structure and files as an existing repository.
A template repository do not need to be created.
This is already part of the template repository for AP195.

A detailed tutorial of the one-time cloning procedure [for creating repository from a teample is found online](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
