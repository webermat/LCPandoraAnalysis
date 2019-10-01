# LCPandoraAnalysis
[![Build Status](https://travis-ci.org/PandoraPFA/LCPandoraAnalysis.svg?branch=master)](https://travis-ci.org/PandoraPFA/LCPandoraAnalysis)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/13061/badge.svg)](https://scan.coverity.com/projects/pandorapfa-lcpandoraanalysis)

Pandora calibration and analysis tools in iLCSoft / Marlin framework 

LCPandoraAnalysis is distributed under the [GPLv3 License](http://www.gnu.org/licenses/gpl-3.0.en.html)

[![License](https://www.gnu.org/graphics/gplv3-127x51.png)](https://www.gnu.org/licenses/gpl-3.0.en.html)

## License and Copyright
Copyright (C), LCPandoraAnalysis Authors

LCPandoraAnalysis is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

PandoraPFA particle flow pattern recognition algorithms reconstruct particles out of physics digitized energy deposits based on tracks and clusters in calorimeters. These classes calibrate the response of these particles. SoftwareCompensation reweights the energy deposits of the calorimeter, based on the energy density of a shower, which is found in a regression step using chi2 minimisation of the total cluster energies.
Here parameters for MuonChamber response and software compensation have been adapted to conditions as they will be present at the CLIC detector.
