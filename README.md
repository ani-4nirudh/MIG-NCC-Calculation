# Description
This repo contains code to analyze images captured using `img_acq_testing` with NCC algorithm and save it's results in a .csv file. For more info, check code comments.

# Build
```
mkdir -p lib build

# Go to build directory
cd build

# Generate makefiles inside build
cmake -s ..

make -j

# Paste the directory containing images collected from img_acq_testing at the path <your_path>/mig_ncc_testing/

# Run the executable from within the build folder
./mig_ncc_testing
```