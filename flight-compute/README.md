#Flight AWS Marketplace Templates
##8-node cluster 

This template creates an 8-node HPC environment, either in an existing user-created network or optionally in an entirely separate cluster network. The template starts with 8 dedicated compute hosts - each with 2 cores and 4GB memory; which is set to automatically scale up and down based on the HPC scheduler load. 

The user is also able to choose a login node instance type, defining the number of cores and memory available to the instance. 

##16-node cluster

This template creates a 16-node HPC environment, either in an existing user-created network or optionally in an entirely separate cluster network. The template starts with 16 dedicated compute hosts - each with 16 Ivy-Bridge cores and 16GB memory; which is set to automatically scale up and down based on the HPC scheduler load. 

The user is also able to choose a login node instance type, defining the number of cores and memory available to the instance. As well as defining a login node instance type - the user is able to specify the default root system disk size for each of the deployed instances. 

##32-node cluster

This template creates a 32-node HPC environment, either in an existing user-created network or optionally in an entirely separate cluster network. The template starts with 32 dedicated compute hosts - each with 32 Haswell cores and 60GB memory; which is set to automatically scale up and down based on the HPC scheduler load. 

The user is also able to choose a login node instance type, defining the number of cores and memory available to the instance. As well as defining a login node instance type - the user is able to specify the default root system disk size for each of the deployed instances. 
