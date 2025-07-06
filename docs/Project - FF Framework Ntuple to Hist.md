# FF Framework Ntuple to Hist
- Need to set this job at all sites:
  - [X] UC:
    - [X] Schedule the job

  - [X] BNL:
    - [X] Update the analysis file; should include the ID file, campaign and path to the input files:
      - [X] These files need to only have the mc20e campaign
      - [X] Update the path to the files
    - [X] Make sure the files have a “.hist-output.root” extension when running the script that will generate the weights
    - [X] Make sure the ANALYSIS.root files are listed in the file list .txt file
    - [X] Run the FF helping scripts that will produce the sum of weights from the analysis file list
    - [X] Update the config file:
      - [X] Update paths:
        - [X] input files
        - [X] input file list
        - [X] output
    - [X] Copy the input files to the appropriate directory
    - [X] Schedule the job

  - [O] SLAC:
    - [X] Update the analysis file; should include the ID file, campaign and path to the input files
    - [X] These files need to only have the mc20e campaign
      - [X] Update the path to the files
    - [X] Make sure the files have a “.hist-output.root” extension when running the script that will generate the weights
    - [X] Make sure the ANALYSIS.root files are listed in the file list .txt file
    - [X] Update the config file:
      - [X] Update paths:
        - [X] input files
        - [X] input file list
        - [X] output
    - [X] Run the FF helping scripts that will produce the sum of weights from the analysis file list
    - [X] Copy the input files to the appropriate directory
    - [ ] Schedule the job

  - [X] NERSC:
    - [X] Update the analysis file; should include the ID file, campaign and path to the input files
    - [X] Make sure the files have a “.hist-output.root” extension when running the script that will generate the weights
    - [X] Make sure the ANALYSIS.root files are listed in the file list .txt file
    - [X] Run the FF helping scripts that will produce the sum of weights from the analysis file list
    - [X] Schedule the job

