# Simulation Workshops

## Initial Setup

1. Open a `terminal` from the Start Menu
2. Install Python using the uv package manager `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
3. Give yourself permissions to run software `Set-ExecutionPolicy ByPass -Scope CurrentUser -Force`
4. Install git so we can download the notebooks and simulation configurations `winget install git.git`
5. Close and open the terminal so the changes take effect
6. Copy the resources for running the workshop to your computer `git clone --recurse-submodules https://github.com/EuropeanAOSummerSchool/eaoss_workshops.git`. This will create a directory called `eaoss_workshops` on your computer.
7. Navigate to the `eaoss_workshops` directory by typing `cd eaoss_workshops`
8. Create a Python environment `uv venv`
9. Activate the environment `.venv/Scripts/activate`
10. Install everything we need to run the workshop software `uv pip install jupyter soapy tqdm`

Everything should now be installed and ready for you to start the workshops.

### Data Analysis Workshops

The data for these workshops can be found [here](https://livenorthumbriaac-my.sharepoint.com/:f:/g/personal/matthew_townson_northumbria_ac_uk/IgDUurERFrl5TqH8XKCQS7fpAeReXVm0MFvU6r3lsPmvf6A?e=foG02e)
