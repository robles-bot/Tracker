# 2025

## July

- [X] Store copies of the crontab/scrontab files used at the AFs in GitHub
- [X] Need to check the two coffea.root files found in my home directory at UC-AF:
  - [X] Make notes or reference for the root code that make the histogram
- [X] Need to check on the script that sends information to the dashboard at all sites and continue to send information from BNL
- [X] Make slides with the diagram found in my notes:
  - [X] Learn how to use mkdocs
  - [X] Use mkdocs mermaid:
    - [X] Should be able to use markdown syntax as shown [here](https://squidfunk.github.io/mkdocs-material/reference/diagrams/#using-sequence-diagrams)
- [X] Fix the Rucio download error; Agree to the updated the AUP


- [X] Continue to work on the BNL Parsing Scripts:
- [X] Check the error caused by the Rucio Job -> Seems to be an error with the job script itself -> Error was with the directory containing previously contained files was missing so "rm -r dir/" resulted in an error
- [X] Log into SLAC after maintenance and work on parsing scripts:
  - [X] Check again later today; checked this morning at 9AM and connection was closing
- [X] Check the crontab file at SLAC
- [X] Fix the coffea job
- [X] Update and schedule the FF job
- [X] Make bubble going from ntuple->Coffea->Hist NOT physlite->coffea->hist
- [X] SLHA -> GenTF -> EVNT
- [X] EVNT -> RecoTF -> DAOD
- [X] PHYSLITE -> Rucio Download
- [X] RHS-Top three can be collapsed into one
- [X] Remove line from DAOD_TRUTH to event loop (no job running on DAOD_TRUTH)
- [X] Update and link the GenTF and Reco_TF/Derivation_TF nodes


- [X] Fix the parsing scripts
- [X] Figure out what is causing this error:
```bash
OSError: [Errno 121] Remote I/O error
```
ChatGPT is suggesting this is a hardware or system-level issue and not a bug in the code.
I figured it out and it was really the Rucio parsing script that was holding all other jobs behind because of how I have the parsing scripts scheduled.
- [X] Set up the SLAC FF -> I need to figure out why I'm getting a type error when inputting the config file at SLAC
- [X] Get to the bottom of this on PDB, insert break points and see why the error is being thrown
- [X] Check the paths and make sure it is still available
- [X] If there is a file that is causing the issue, wrap it using a try-except and have it give an error message and give me the name of the file that is missing/faulty
- [X] Keep the dashboard populated and don't move until it is guaranteed that there won't be issue
- [X] Check on the jobs; they aren't posting to Kibana -> Not sure why they aren't posting, the script works when I run it without using crontab


- [X] Compare Coffea, FF, and EventLoop histogram

