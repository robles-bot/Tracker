# Current

TODO:

## General
- [ ] Learn how to use PDB
- [ ] Learn how to use Pyinstrument
- [ ] Implement new methods of parsing and cases as nets for the parsing scripts
- [ ] Check when Ilija will be back so I can prepare the migration over to the new parsing scripts
- [ ] Look into version control
- [ ] Have two jobs for FF and Coffea running; each with different number of cores/threads:
  - [ ] Test coffea with a single node and x amount of threads

## BNL

- [ ] Update the FF code so that it matches what is being used at SLAC
- [ ] Fix the parsing script used by the coffea job
- [ ] update the parsing script to include the changes Ilija suggested; I just need to make sure the json docs contain "token" and "kind"; send them one by one

## SLAC

- [ ] Fix the parsing script used by the coffea job
- [X] Fix the script that runs the parsing scripts; ssh iana "commands"
- [ ] Figure out what is causing the EVNT-EL9 Error

## UC

- [ ] Parse Ntuple -> Hist log files and compare both FF and Coffea
- [ ] Update the FF code so that it matches what is being used at SLAC
- [ ] Fix the parsing script used by the coffea job
- [X] Update the error handling in the parsing scripts for EVNT

## NERSC

- [ ] Update the FF code so that it matches what is being used at SLAC
- [ ] Fix the parsing script used by the coffea job

## Site

- [ ] Add a legend to the flowchart -- red is scripts and blue is data formats


# Dumps
[Dump - mkdocs](Dump - mkdocs.md)

[Dump - Meetings](Dump - Meetings.md)

# Projects
[Project - Coffea Framework Ntuple to Hist](Project - Coffea Framework Ntuple to Hist.md)

[Project - FF Framework Ntuple to Hist](Project - FF Framework Ntuple to Hist.md)

[Project - Event Loop Ntuple to Hist](Project - Event Loop Ntuple to Hist.md)

[Project - Parsing Script](Project - Parsing Script.md)


# Ideas

- Schedule the parsing script at BNL: /atlasgpfs01/usatlas/data/jroblesgo/parsing_jobs/

DONE:

[Completed Tasks](Completed Tasks.md)


