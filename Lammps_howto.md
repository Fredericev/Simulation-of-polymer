# Lammps on Mac
This is a conculsion for Lammps install and running include coding on Macbook.

If operating system is windows or Linux, please follow [LAMMPS](https://docs.lammps.org/Install_mac.html)

## Install on Mac
Installing [Homebrew](https://brew.sh/) is the first step to built and configure LAMMPS on mac.

- command on terminal:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

After installing Homebrew, commands of installation(LAMMPS) is:
`% brew install lammps`

Test of installation:
`% brew test lammps -v`

The openkim-models package:
`% brew install openkim-models`
