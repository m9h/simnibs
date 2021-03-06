.. _conda-install:

Install Using Conda (Advanced)
===============================

It is also possible to install SimNIBS using the `Conda <https://docs.conda.io/en/latest/>`_ package manager, present for example in the `Anaconda <https://www.anaconda.com/>`_ and `Miniconda <https://docs.conda.io/en/latest/miniconda.html>`_ Python distributions.


1. Go to the latest `release page <https://github.com/simnibs/simnibs/releases/latest>`_ 

2. Download the :file:`environment_*.yml` file for your operating system

3. Create and activate the :code:`simnibs_env` conda environment

  .. code-block:: bash
  
     conda env create -f environment_*.yml
     conda activate simnibs_env
  
  \

4. Install SimNIBS using :code:`pip`

  .. code-block:: bash
  
     pip install -f https://github.com/simnibs/simnibs/releases/latest simnibs

  \

5. (Optional) to install the Menu icons, set-up file associations, the matlab library and add SimNIBS binaries to the system path, run the :code:`postinstall_simnibs` script. Type :code:`postinstall_simnibs -h` for help