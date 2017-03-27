# multibeam-lcmtypes

Collection of LCM types for multibeam sensors (e.g. DVL/LIDAR/RADAR/SONAR).

** NOTE: these are NOT intended to be fixed types; they are very likely to change in order to support more sensors. **

## Dependencies
* [LCM]()

## Installation 

Run `make` to build the pod locally (build output will be located in `multibeam-lcmtypes/pod-build`).


## Contents
* `range_t` - single range measurement
* `range_scan_t` - collection of range measurements
* `ping_t` - two-dimensional ping

## Usage

Add `multibeam-lcmtypes` to the collection's `tobuild.txt` - when building the collection, `multibeam-lcmtypes` will be built and installed in the collection's build directory.

## Notes
This software is constructed according to the Pods software policies and
templates.  The policies and templates can be found [here](http://sourceforge.net/projects/pods).
