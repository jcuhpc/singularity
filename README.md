# singularity
A JCU repository for singularity container builds.

This repository, created by JCU HPC staff, should contain a few scripts
and a number of "metadata" files (e.g., singularity definition file
templates) for creation of singularity container(s).  Containers built
using this repository are based on Ubuntu or Miniconda bases.  The
scripts & metadata have been used to create 300+ singularity containers
and environment module files for JCU with an average human time
investment of <20s per container.

Use of Singularity HPC may be a better choice for many/most people.
However, I found the cost (human time) of SHPC to be high when viewed
across hundreds of application/workflow based containers that I have
been building to replace more traditional installs.  Sustainable support
for "Reproducible Research" on JCU HPC systems has been the driver.

In most cases, if you are looking to install the "latest" conda/ubuntu
packaged version, you will not need to specify a version to build a
container using the scripts provided here.  The scripts use metadata
on anaconda.org and/or packages.ubuntu.com in an attempt to detect the
latest verion available.

This respository also houses some singularity definition files for
container creation that lies beyond the capabilities of MVP scripts
that can be found here.

In time, an ability to support automatic/scheduled installation of
new versions will be built in, where possible.

NOTE:  HPC system administrators have built this repository.
Development of software does not appear anywhere in our PDs.
If the contents of this repository work for you, we would
would appeciate hearing reports of "container works" from a
research use point of view.  We accept constructive feeback,
but cannot provide any guarantee of bug fixes or updates.

REPOSITORY CREATORS

Dr. Whitney Mallett

Mr. Wayne Spagnol

