# DMD

## Development

DMD is a general purpose code to perform real time density matrix dynamics.
Please clone this repository to make changes or to add new features and then initiate pull/merge request
for changes and contributions to be incorporated.

## Installation

Create build directory at the same level as src directory in the main DMD directory. Change make.inc to point to dependencies according to your specific system ennvironment.

To install:
1. Make sure intel mpi compiler and command `mpiicpc` exist.
2. GSL and MKL must be installed and ensure `MKLROOT` is correct.
3. Modify `GRL_DIR` in `make.inc` and `SRC_DIRS` in `Makefile`, if necessary.
4. If there is no "build" directory, create it.
5. Issue `make` in the main directory. 