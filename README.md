[![memote tested](https://img.shields.io/badge/memote-tested-blue.svg?style=plastic)](https://authorname.github.io/syn6803)

# _Synechocystis_ sp. PCC 6803

This repository contains the files for the genome scale reconstruction of _Synechocystis_ sp. PCC 6803: iRH783. It is based on the genome [BA000022](https://www.ncbi.nlm.nih.gov/nuccore/BA000022).

## Files

The repository contains the following files:
1. Synechocystis_6803.xml - The SBML of the reconstruction.
2. Synechocystis_6803.yml - A YAML version of the reconstruction.
3. Synechocystis\_6803_constrained.xml - A constrained version of the same reconstruction. The medium is constrained in a way that the only carbon source is CO<sub>2</sub> and the only nitrogen source is NO<sub>3</sub>. Photon uptake is limited to match a growth rate of 1 h<sup>-1</sup>.
4. Synechocystis\_6803_constrained.yml - The YAML version of the same constrained model.
5. iRH783_memote.html - A MEMOTE report for the constrained version of the model.

## Usage

All `memote` commands have extensive help descriptions.

1. For simple command line testing, check out `memote run -h`.
2. To generate a pretty report, check out `memote report snapshot -h`.

## Testing the Model with Continuous Integration

Currently, we can enable continuous model testing using Travis CI. All you have
to do is:

1. Create a [GitHub](https://github.com/) account.
2. Create an account at https://travis-ci.org using your GitHub account.
3. Run `memote online`.
4. A history report will be publicly visible at https://authorname.github.io/syn6803.

---

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
