# Useful-Packages-for-Cell-Trajectories-Quantification
This repository contains several useful but small python packages which helps you to quantify the cell trajectories storaged in XML file and exported by TrackMate plugin in Fiji.

## 1. TrackusRevelio 
'TrackusRevelio' is a Python package designed to unravel and extract tracks from XML files exported by TrackMate in Fiji/ImageJ. This tool helps in converting the XML data into a Python list containing the instaneous speeds of the particles/cells/tracks for further analysis and processing. Please read the `README.md` for this package to know how to use it.

You can install it via pip:
```sh
pip install trackus-revelio
```

## 2. velocityvortex 
`velocityvortex` is a Python package for calculating the Velocity Autocorrelation Function (VAF) from XML files exported by TrackMate in Fiji/ImageJ. This tool converts tracking data into velocity vectors and computes their autocorrelation over time, helping analyze cell trajectories and dynamics. Please read the `README.md` for this package to know how to use it.

You can install it via pip:
```sh
pip install velocityvortex
```
