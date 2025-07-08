# Parsing Script - BNL

- Focusing on this site

## Structure - rucio_parsing.py

- Line 8-27 initialize the input variables: job name, file names, script path, and AF site
- Line 30 initializes the data handling class using the previously defined variables
- Line 33 obtains a list of the paths, example: '/atlasgpfs01/usatlas/data/jroblesgo/benchmarks/2025.07.07T19'
- Line 36 obtains a list of paths to the job files, example: '/atlasgpfs01/usatlas/data/jroblesgo/benchmarks/2025.07.01T18/Rucio/rucio.log'
- Line 38-49 is a for loop that will populate a list with dictionaries containing the parsed data
- Line 53-57 obtains the submit time, in epochs, of the last entry sent to the dashboard
- Line 62-64 runs a for-loop over the list of dictionaries looking for the index of the dictionary that contains the previously acquired submit time
- Line 68-71 run a for-loop and creates a new list containing dictionaries starting from the i+1 index obtained in the previous step
- Line 75 sends the information to the dashboard using the previously obtained list
- Line 77-83 appends the dictionaries that were just sent to a file


## Already Being Parsed

- [X] Rucio Job
- [ ] EVNT:
  - [ ] EL9
  - [ ] CentOS7
- [ ] TRUTH3:
  - [ ] EL9
  - [ ] CentOS7
- [ ] Ntuple->Hist:
  - [ ] FF
  - [ ] Coffea
