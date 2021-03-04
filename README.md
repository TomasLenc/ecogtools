# ecogtools
A collection of tools for analyzing electrocorticography data.

For some demos of how to use this code, check out this interactive Binder instance:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/choldgraf/ecogtools)


---

Install with python 3.5

    MNE-Python 0.17 was the last release to support Python 2.7
    MNE-Python 0.18 requires Python 3.5 or higher
    MNE-Python 0.21 requires Python 3.6 or higher


Download MNE 0.13 as zip from [here](https://github.com/mne-tools/mne-python/releases/tag/v0.13) and install directly from the zip file: 

`pip install $$$.zip`

---

also install Holdgraf's package colorbabel from github

`python -m pip install git+https://github.com/choldgraf/colorbabel`

--- 

to import ecogtools in notebooks, you need to add the parent directory on sys.path: 
```
import sys
sys.path.append("../") # go to parent dir
import ecogtools
```

