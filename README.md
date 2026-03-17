# 📘 Setting Up Jupyter Notebook with the R Kernel  
A complete guide to help you run R code locally inside Jupyter Notebook for your Hands‑On Lab.

---

## ✅ 1. Install R and RStudio (One‑Time Setup)

Before using R inside Jupyter Notebook, you must install R on your computer.

### Install R  
Download and install R from the official CRAN website:  
🔗 [https://cran.r-project.org](https://cran.r-project.org)

### Install RStudio (Optional but Recommended)  
RStudio makes it easier to run the commands needed to install the R kernel.  
🔗 [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)

> **Note:** RStudio is not required for the HOL itself, but it simplifies setup.

---

## ✅ 2. Install the R Kernel for Jupyter (One‑Time Setup)

You must run these commands **inside R or RStudio**, not inside Jupyter.

1. Open **RStudio** (or the R console).  
2. Run the following commands:

```r
install.packages("IRkernel")
IRkernel::installspec()
```
3. Close and restart Jupyter Notebook or JupyterLab if they are currently running.
4. When creating a new notebook, you should now see R listed as a kernel option.

## ✅ 3. Launch Jupyter Notebook with the R Kernel
1. Open your terminal, command prompt, or Anaconda Prompt.
2. Navigate to your project folder:

```bash
cd path/to/your/folder
```
Start Jupyter Notebook:
```bash
jupyter lab
```
In the browser window that opens, click:
New → R
