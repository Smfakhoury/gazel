## ICSE 2021 Demonstration Track Replication Package
#### **"Gazel: Supporting Source Code Edits in Eye-Tracking Studies"**

**Authors:** [Sarah Fakhoury](https://sarahfakhoury.com), [Devjeet Roy](https://devjeetr.github.io), Harry Pines, Tyler Cleveland, Cole Peterson, [Venera Arnaoudova](https://www.veneraarnaoudova.com), [Bonita Sharif](https://www.shbonita.me), and [Jonathan Maletic](http://www.cs.kent.edu/~jmaletic/). 

:movie_camera: Demo Video:  coming soon!!

***

## iTrace-Atom plugin
The iTrace-Atom plugin can be downloaded from atom's package manager, apm. 

Link to package: https://atom.io/packages/itrace-atom

Link to repository: https://github.com/devjeetr/itrace-atom

All documentation, including instructions for how to install the package and use the plugin are can be found at both links. Sample data can be found in the folder 'sample-experiment'.

***

## gazel 
*pronounced: | ɡəˈzel |*

gazel can be downloaded from PYPI 

Link to library: https://pypi.org/project/gazel/
Link to repository: https://github.com/devjeetr/gazel

Instructions for installation, documentation of base functionality, and a jupyter notebook with the demo and sample data can be found at the link above.

***
### Evaluation 
To ensure a reproducible experiment with little variation, the evaluation of iTrace-Atom for high speed eye trackers was conducted using controlled gaze data generated by a script. 

Link to the script: https://github.com/devjeetr/itrace-mocker

Results of the experiment (% indicates percentage of gazes retained):
| Data Sampling Rate | Visual Studio | Eclipse | Atom   |
|--------------------|---------------|---------|--------|
| 60Hz               | 64.16%        | 100%    | 100%   |
| 120Hz              | 37.43%        | 100%    | 100%   |
| 150Hz              | 35.31%        | 98.43%  | 99.86% |
| 300Hz              | 19.66%        | 94.86%  | 99.95% |
| 1000Hz             | 6.38%         | 29.17%  | 99.92% |
| 1200Hz             | 5.50%         | 24.29%  | 99.79% |
| 2000Hz             | 3.73%         | 14.39%  | 99.73% |
