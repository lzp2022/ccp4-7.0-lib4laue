# ccp4-7.0-lib4laue
Minimum required libraries in ccp4-7.0 for building LAUEGEN

# Installation
Install dependencies:

**Centos_7.9 (come with py27)**

`yum install gcc-c++ gcc-gfortran m4 libXt-devel xorg-x11-fonts-75dpi`

**Ubuntu_22.04**

`sudo apt install python2.7 gfortran g++ m4 make libxt-dev xfonts-75dpi` 

#
Download build script and build LAUEGEN with ccp4-7.0 minimum libraries:

  `wget -c https://raw.githubusercontent.com/lzp2022/ccp4-7.0-lib4laue/main/build-lauegen`
  
  `cat build-lauegen | tr '\r' ' ' > build`

  `sh build`
#


**Citation:**

https://doi.org/10.1107/S1600577521001326

The Daresbury_Laue software source code (identical versions) may be downloaded from any one of the following three weblinks:

https://www.chess.cornell.edu/sites/default/files/inline-files/Daresbury_laue.tar.gz

https://zenodo.org/record/4381992#.X-B7Z1DgrtQ

http://web.hku.hk/~qhao/Daresbury_laue_Dec2020.tar.gz

The weblink for the full information about the suite is now https://web.archive.org/web/20001024010254/http://www.dl.ac.uk/SRS/PX/jwc_laue/laue_top.html.
