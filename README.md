![tutorialpromo](images/tutorial_banner.PNG)

# PVSC50 Python Tutorial
Welcome! The goal of this tutorial is to introduce attendees to the
[pvlib python](https://pvlib-python.readthedocs.io/) package for modeling
production of PV systems. The tutorial is divided into 5 sections and several
appendicies.

## Tutorial Summary:
* **Tutorial 0**: Introduction to the tutorial, the lesson plan, and resources (~30 minutes)
* **Tutorial 1**: Access TMY weather data and visualize monthly irradiance data (~30 minutes)
* **Tutorial 2**: Calculate solar position, plane-of-array irradiance, and
  visualize average daily insolation (30 minutes)
* **Tutorial 3**: Estimate module temperature from ambient (~20 minutes)
* **Tutorial 4**: Use POA irradiance and module temperature to model output power
  from a single module (~20 minutes)
* **Tutorial 5**: Combine modules to form strings, calculate inverter efficiency
  and total array output (~independent study)
* **Tutorials Appendices**: More tutorials on a variety of fun topics (~independent study)

## Tutorial Setup
These tutorials are made with [Jupyter](https://jupyter.org), which is a
browser based interactive Python notebook that allows you to run the tutorials
in the cloud without any additional setup. On the day of the tutorial, we will
use [Google Colaboratory](https://colab.research.google.com/).

### Google Colaboratory
To run these tutorials in [Google Colaboratory](https://colab.research.google.com/)
you can click the button below:

<a target="_blank" href="https://colab.research.google.com/github/PVSC-Python-Tutorials/PVSC50/blob/main/Tutorial%200%20-%20Overview.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

You can also select Colaboratory from the launch icon at the top of each tutorial
in the [Jupyter book](https://pvsc-python-tutorials.github.io/PVSC50/index.html).

#### Installing Requirements
When using Google Colaboratory, you must uncomment the first cell that installs
the tutorial requirements.

    !pip install -r https://raw.githubusercontent.com/PVSC-Python-Tutorials/PVSC50/main/requirements.txt

### Jupyter Books

The full tutorial is hosted as a [Jupyter book](https://jupyterbook.org/intro.html).
This book has navigation, search, and can be used to launch each book in Colaboratory.

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](<https://pvsc-python-tutorials.github.io/PVSC50/index.html>)

### My Binder

The tutorials will remain available on GitHub, and you can run
the tutorial anytime in [Binder](https://mybinder.org) by clicking the
following link:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PVSC-Python-Tutorials/PVSC50/main)

### Locally

You can also run the tutorial locally with
[miniconda](https://docs.conda.io/en/latest/miniconda.html) by following thes
steps:

1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

1. Clone the repository:

   ```
   git clone https://github.com/PVSC-Python-Tutorials/PVSC50.git
   ```

1. Create the environment and install the requirements. The repository includes
   a `requirements.txt` file that contains a list the packages needed to run
   this tutorial. To install them using conda run:

   ```
   conda create -n pvsc50 jupyter -c pvlib --file requirements.txt
   conda activate pvsc50
   ```

1. Start a Jupyter session:

   ```
   jupyter notebook
   ```

1. Use the file explorer in Jupyter lab to browse to `PVSC50`
   and start the first Tutorial.


### Licensing

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
