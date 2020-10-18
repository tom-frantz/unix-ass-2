# Unix Assignment 2

Student Name: Thomas Frantz
Student Number: s3719834
Raspberry Pi Type: 3

## Contents
- `.config`: This file contains the config for the build scripts.
- `.gitignore`: The gitignore for the repository
- `gitlog`: An up to date version of the git history.
- `report.md`: The report which details the performance while compiling the kernel. Also contains a figure describing the temperature of the kernel.
- `kernel_performance_data`: The data used to create the kernel png for the report
- `kernel_performance.png`: The graph used in the report


### Scripts

Each script will have an associated `man` page, which will be named `man_{file_name}` where `{file_name}` is the name ofthe script involved

- `initial_build_kernel`: The first template file used to compile the kernel and create a .config file. 
- `build_kernel`: The required script for the building of the kernel
- `first_performance`: The temperature tracking script
- `second_performance`: The LED flashing script
- `kernel_graphing_script`: The graphing script

