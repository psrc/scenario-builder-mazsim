# scenario-builder-mazsim
Uses psrc_mazsim race scenario outputs to adjust the 2050 soundcast landuse files

## Instructions
1. Download and unzip [mazsim results h5 file and blocks csv file](https://psrcwa-my.sharepoint.com/:u:/r/personal/jkolberg_psrc_org/Documents/Shared/race_scenario_mazsim_results.zip?d=wf9703192074d4014a73008b883e54ce7&csf=1&web=1&e=yg8IE4) to inputs/mazsim_results

2. Setup up UV venv:
    
    `uv sync`

2. Run the prepare_inputs.ipynb jupyter notebook selecting the venv as the kernel

3. Run scenario_builder:
    
    `uv run soundcast_landuse_scenario_builder run -c project/race_scenario`
