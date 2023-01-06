# Lammps on Mac
This is a conculsion for Lammps install and running include coding on Macbook.

If operating system is windows or Linux, please follow [LAMMPS](https://docs.lammps.org/Install_mac.html)

## Install on Mac
Installing [Homebrew](https://brew.sh/) is the first step to built and configure LAMMPS on mac.

- Command on terminal:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

- After installing Homebrew, commands of installation(LAMMPS) is:
`% brew install lammps`

- Test of installation:
`% brew test lammps -v`

- The openkim-models package:
`% brew install openkim-models`

## Running LAMMPS on Mac (Simulation of Polymer as a example)
- Commands:

-Under the current file：`mpirun -np 4 lmp_mpi -in in.file`

-Give the file path：`mpirun -np 8 /path/to/lammps/src/lmp_mpi -in in.file`

Once the table and data as shown in the figure appear, congratulations you have successfully run！！！:+1:


<img width="447" alt="截屏2023-01-06 00 25 17" src="https://user-images.githubusercontent.com/74882572/210906610-d889e2a1-ada0-4158-89c3-31d34f613938.png">


