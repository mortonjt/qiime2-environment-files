# qiime2 environment files

[![Build Status](https://travis-ci.org/biocore/qiiem2-environment-files.svg?branch=master)](https://travis-ci.org/mortonjt-qiime2-environment-files)


This is a repository of extended environment, enabling other tools in qiime2 library to be bundled with the qiime2 install.
See [qiime2 environment files](https://github.com/qiime2/environment-files).

Right now, the following tools are bundled with qiime2

- [mmvec](https://github.com/biocore/mmvec)

- [songbird](https://github.com/biocore/songbird)

- [deicode](https://github.com/biocore/DEICODE)

- [qurro](https://github.com/biocore/qurro)

# Local installation

Download the environment file based on your OS and version.  Then run the following

```
conda env create -q -n test_env --file <env.yml>
```

# Contributions

Contributions are welcome - make sure to submit a pull request to modify the conda environment file.
*Conda* installations are preferable, and tests need to pass for both MacOSx and Linux.
