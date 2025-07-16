# Current

TODO:

## General
- [ ] Learn how to use PDB
- [ ] Implement new methods of parsing and cases as nets for the parsing scripts
- [ ] Check when Ilija will be back so I can prepare the migration over to the new parsing scripts
- [ ] Look into version control

## BNL

- [ ] Schedule EVNT Parsing scripts
- [ ] Update the FF code so that it matches what is being used at SLAC

## SLAC

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


## UC

- [ ] Parse Ntuple -> Hist log files and compare both FF and Coffea
- [X] Compare Coffea, FF, and EventLoop histogram
- [ ] Update the FF code so that it matches what is being used at SLAC

## NERSC

- [ ] Update the FF code so that it matches what is being used at SLAC

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



DONE:

[Completed Tasks](Completed Tasks.md)


