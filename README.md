# README

Welcome to this private Jupyter notebooks repository on GitHub. This repository contains several Jupyter notebooks for BeamNG.drive. Each notebook has a unique purpose and is available for non-commercial use under the Creative Commons License.

Here is a brief overview of the notebooks to find in this repository:

## Jupyter notebooks

### OpenStreetMap with BeamNG.drive

**WORK IN PROGRESS** `useOSMdataWithBeamNg.ipynb` - In this example, we download OpenStreetMap data for San Francisco and use the OSMnx library to generate a network graph of the streets and roads in the area. We then use the Scenario and Road classes in BeamNGpy to create a scenario that includes roads based on the OpenStreetMap data. Finally, we add a vehicle to the scenario and use the ai_set_route method to drive the vehicle along the roads in the scenario.

#### Setting up the Conda environement

1. Ensure you have Conda installed on your system.
2. Open your terminal or Anaconda Prompt, navigate to the directory containing the `environment.yml` file, and create a new Conda environment called 'beam_ng' with the specified packages: `conda env create -f environment.yml`
3. Activate the `beam_ng` environment: `conda activate beam_ng`
4. Launch the Jupyter Notebook: `jupyter notebook`
5. Now, open the Jupyter Notebook file (`useOSMdataWithBeamNg.ipynb`) and run the code cells.

## Additional information

All Jupyter notebooks in this repository are available under the Creative Commons License for Non-Commercial Use. This means that you are free to use, modify, and share these projects as long as it is for non-commercial purposes. If you wish to use these Jupyter notebooks for commercial purposes, please contact the owner of this repository for licensing information.

If you have any questions or feedback, please do not hesitate to reach out to the owner of this repository.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">
    <img
        alt="Creative Commons License"
        style="border-width:0"
        src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png"
    />
</a>
<br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
