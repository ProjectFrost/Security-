- - -
Source:
Date Created:  28-12-2023
Tagged Concepts:
- #Domain_2/Replication/VM  
Type: [[Final Note Template]]
- - - 


Where a copy of a VM is copied across to another physical host. With** live migration**, VM files can be copied across onto a second 
physical host with **no downtime**

**With [[SAN]] migration**, the files for a virtual machine are not copied from one server to another and thus downtine is minimized.

**Each node in the hypervisor cluster can see the storage LUN** and has a cluster disk resource for the LUN.

**VM migration in this scenario means transferring control of the storage from one hypervisor host to another**

While terminology differs by vendor, this capability exists forHyper-V, VMware, and other popular Type 1 hypervisors