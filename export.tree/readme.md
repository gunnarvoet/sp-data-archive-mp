[![DOI](https://zenodo.org/badge/552233487.svg)](https://zenodo.org/badge/latestdoi/552233487)

# Samoan Passage Moored Profiler Data Archive

Moored Profiler data from the 2012 (RR1209) and 2014 (TN305) Samoan Passage cruises.

The data were collected under National Science Foundation grants OCE-1029268 and OCE-1029483.

Data are stored in human-readable format at https://osf.io/7b8fn/ and can be downloaded manually from there.

A repository containing data in *git-annex* / *datalad* format is located at https://osf.io/9uxr8/ and connected to this repository. To access the data this way, clone the bare dataset repository (without the data files) via:
```
datalad clone https://github.com/gunnarvoet/sp-data-archive-mp
```
In a second step, obtain the data from the OSF repository via:
```sh
datalad get -r -d sp-data-archive-mp
```
More information on *git-annex* and *datalad* can be found in the [DataLad Handbook](https://handbook.datalad.org/en/latest/index.html).

The parent Samoan Passage Data Archive repository containing further datasets is located at https://github.com/gunnarvoet/sp-data-archive/.
