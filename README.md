# singularity
A JCU repository for singularity container builds.

This repository, created by JCU HPC staff, should contain a script and
"metadata" files for creation of singularity container(s) with an
embedded conda environment.  This repository was used to rapidly create
100+ singularity containers for JCU.  In most cases, a version for software
is not required for container build - this environment uses metadata on
anaconda.org in attempt to detect latest version available.  In time,
an ability to support automatic/scheduled installation of new versions
will be built in (success dependent on metadata in anaconda.org).

This respository also houses singularity definition files for creation
of containers which do not house a conda environment.

Development of this repository is primarily for internal JCU use.  If
it works for you, we would appeciate hearing reports of "container
works".  If it doesn't work for you, we cannot provide any guarantee
on response time to constructive feedback.

Use of Singularity HPC may be a better choice for others.
