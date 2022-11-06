## Create a New Conda Environment

**On Windows:** Open an **Anaconda Powershell Prompt** (Start -> Anaconda3 -> Anaconda Powershell Prompt). 

**Other operating systems:** Open a terminal. 

On the command line prompt you should see an indicator which Python environment is currently active, e.g. `(base) PS C:\Users\me`

The token `(base)` shows the active environment.

The fastest way to create the necessary conda environment named `eeng` for this course is:

```
conda create -c conda-forge -n eeng python=3 jupyterlab numpy scipy matplotlib pandas ipywidgets pyserial bqplot
```

This command installs packages from the **conda-forge** software 'channel'. A channel is a online software source, a huge repository providing the software packages for installation.

After successful creation **activate** the environment and start **jupyter-lab** from within the environment.

```
conda activate eeng

jupyter-lab
```